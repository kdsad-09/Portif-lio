# ProfileLinkD v3 — calculadoras separadas + etapa 3

## Abrir localmente
Extraia **todo** o ZIP e abra `index.html`. A navegação leva a `calculadoras.html`, `informativos.html` e `artigo.html`.

## Arquivos
- `index.html`: portfólio e atalhos, sem calculadora embutida.
- `calculadoras.html`, `calculadoras.js`: central de cálculos.
- `informativos.html`, `artigo.html`, `publicacoes.js`: biblioteca e artigos individuais.
- `editor.html`, `editor.js`: editor **local**, sem autenticação, que exporta `articles.js`.
- `articles.js`: base estática de artigos; edite/publice via GitHub.
- `styles.css`, `stage21.css`, `v3.css`, `main-v3.js`: visual e navegação.

## Publicar artigos (Etapa 3)
1. Abra `editor.html` no computador; preencha e adicione os artigos.
2. Clique em **Exportar articles.js**.
3. Faça backup do `articles.js` antigo e substitua pelo arquivo exportado.
4. Teste `informativos.html` e `artigo.html`.
5. Envie os arquivos para o repositório GitHub Pages. A publicação ocorrerá após o deploy da branch.

**Limitação:** editor local não sincroniza entre dispositivos, não salva rascunhos ao fechar a página e não publica sozinho. O editor não deve ser apresentado como painel online protegido por senha. Para CMS real, será necessário autenticação e um serviço adicional.

## Legislação / manutenção
A calculadora de salário é uma **simulação simplificada** para empregado CLT com salário fixo e dependentes para IR, competência **2026**. Implementa tabela progressiva do INSS, dedução mensal de dependente e desconto simplificado, tabela progressiva IRRF e redução mensal de 2026. Não calcula benefícios, adicionais, pensão alimentícia, situações de múltiplas fontes pagadoras ou outros casos especiais. Verifique a folha real e as regras da competência.

Fontes oficiais:
- INSS: https://www.gov.br/inss/pt-br/direitos-e-deveres/inscricao-e-contribuicao/tabela-de-contribuicao-mensal
- Receita Federal: https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/tabelas/2026
- Exemplos: https://www.gov.br/receitafederal/pt-br/assuntos/meu-imposto-de-renda/tabelas/exemplos-de-aplicacao-da-lei-15-270-2025

**Não há atualização automática de legislação em GitHub Pages.** Para manter resultados atuais, será necessário revisar periodicamente as fontes oficiais, atualizar as tabelas e validar os testes antes de cada nova competência. Recomenda-se exibir a competência em todas as calculadoras tributárias.

## Publicar GitHub Pages
Suba os arquivos na raiz do repositório e ative `Settings → Pages → Deploy from a branch → main / root`. Não requer servidor, Python ou banco de dados.
