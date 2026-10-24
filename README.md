# ProfileLinkD 3.1 — publicação no GitHub Pages

## Novidades
- Cartão profissional na coluna esquerda da seção Sobre mim.
- Artigos no formato pôster informativo, com tipo, situação, fontes e leitura individual.
- Dois exemplos editoriais: CPC 51 (com fontes oficiais) e jornada/escala de trabalho (guia sem afirmações sobre propostas legislativas).
- Editor local com campo de formato e situação normativa.
- Estado vazio para pesquisa sem resultados.

## Publicação
1. Faça backup dos arquivos atuais do repositório `Portif-lio`.
2. Extraia o ZIP e envie **os arquivos de dentro da pasta** à raiz do repositório (branch `main`), substituindo os existentes.
3. Confirme que `index.html`, `articles.js`, `v31.css`, `editor.html`, `informativos.html` e demais arquivos estão na raiz.
4. Aguarde a publicação pelo GitHub Pages e atualize com Ctrl+F5.

## Como criar novos pôsteres
Abra `editor.html` localmente, preencha título, formato, situação, resumo, texto e fontes. Clique em Adicionar ao arquivo e em Exportar articles.js. Substitua o arquivo `articles.js` do GitHub pelo exportado. **O editor não publica automaticamente.** É público e não tem autenticação; não inclua informações confidenciais.

## Atenção às notícias e normas
- Sempre registre a data, situação (proposta/aprovada/vigente), âmbito de aplicação e fontes oficiais.
- CPC 51: a CVM determinou adoção obrigatória para companhias abertas em exercícios iniciados a partir de 01/01/2027 (Resolução CVM 237). Confira a aplicação para outros tipos de entidade.
- Escalas e jornadas: não apresente propostas de lei como regras vigentes.
- Calculadoras permanecem simuladores em validação; não são atualizadas automaticamente.

## Testes sugeridos
Pesquise por `CPC 51`, selecione o filtro `Trabalho`, abra um artigo, teste exportação do editor e confira o layout em desktop e celular.
