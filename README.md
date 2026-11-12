# Projeto de Loja — pacote para revisão e integração

Este repositório reúne as páginas HTML capturadas, seus arquivos JavaScript, CSS, imagens e recursos locais, organizados por etapa do fluxo.

## Fluxo previsto

1. `ml` — página inicial
2. `produto` — página do produto
3. `checkout-seguro` — etapa de checkout seguro
4. `checkout-pagamento` — seleção/etapa de pagamento
5. `novo-endereco` — cadastro de endereço
6. `pix` — etapa Pix

Os arquivos originais foram mantidos dentro de cada pasta de página para preservar caminhos relativos de imagens, scripts e estilos.

## Onde estão as páginas

Consulte `LEIA-ME.txt` e `MAPA-DO-PROJETO.txt` para os caminhos completos de cada HTML e o inventário de recursos.

## Importante antes de publicar

- Este pacote é uma base de trabalho para revisão. **As páginas ainda não foram conectadas/testadas como um fluxo completo.**
- A cópia local de uma página não garante que APIs, serviços externos, geração/cobrança Pix ou processamento de pagamentos estejam disponíveis.
- Antes de usar em produção, substitua qualquer marca, logotipo, texto, domínio ou elemento visual de terceiros que possa sugerir afiliação não autorizada. Apresente claramente a identidade da sua própria loja.
- Integre pagamentos somente por meio de um provedor legítimo, com credenciais próprias e ambiente de testes; não armazene dados completos de cartão nem simule comprovantes ou pagamentos.
- Não coloque chaves privadas, tokens, senhas ou credenciais neste repositório.
- Preserve os arquivos `assets/` e `__l5e/` junto da página correspondente: vários HTMLs dependem deles.

## Como enviar ao GitHub

1. Extraia este ZIP.
2. Crie um repositório vazio no GitHub.
3. Envie o conteúdo da pasta `Projeto-Loja-GitHub` (não apenas o ZIP).
4. Mantenha `README.md`, `LEIA-ME.txt`, `MAPA-DO-PROJETO.txt` e todas as pastas de `paginas/`.

## Estado desta entrega

Organização de arquivos e documentação apenas. Nenhum botão, rota, integração, checkout ou aparência foi alterado nesta etapa.
