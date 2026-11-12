# Handoff para IA/desenvolvedor

Objetivo: revisar o código existente e implementar o fluxo legítimo da loja, mantendo o visual aprovado.

## Ordem funcional desejada
`ml -> produto -> checkout-seguro -> checkout-pagamento -> novo-endereco -> pix`

## Regras para a revisão
1. Começar identificando cada HTML de entrada e seu bundle JS correspondente.
2. Rastrear eventos de clique, rotas, estado local/sessionStorage e parâmetros de URL antes de editar.
3. Não adicionar `onclick` inline sem confirmar como o framework registra eventos.
4. Não remover bundles, CSS, imagens ou scripts de rastreamento sem mapear dependências.
5. Fazer mudanças pequenas, documentadas e testáveis, uma etapa por vez.
6. Testar o fluxo em ambiente de homologação, incluindo validação de formulário e retorno do provedor de pagamento.
7. Usar identidade visual própria da loja e checkout transparente; não apresentar a loja como Mercado Livre nem sugerir endosso/afiliação que não exista.
8. Usar integração oficial do provedor de pagamento. O pacote capturado pode conter apenas a interface e não comprova que exista backend de pagamento funcional.

## Limites do pacote
A estrutura contém páginas estáticas exportadas/capturadas e bundles compilados. Os bundles podem estar minificados e não equivalem ao código-fonte original do projeto Lovable. Se houver acesso ao projeto original, prefira exportar o código-fonte completo antes de refatorar.
