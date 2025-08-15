# GitHub Pages + Formulário HTML (Formspree)

Este repositório contém um formulário HTML pronto para ser publicado no **GitHub Pages**.
As submissões são enviadas para a **Formspree** (não requer backend).

## Como usar

1. Crie uma conta gratuita em https://formspree.io e crie um formulário.
2. Copie o **endpoint** do seu formulário (ex.: `https://formspree.io/f/abcdwxyz`).
3. Edite o arquivo `index.html` e substitua `SEU_ID_AQUI` pelo ID do seu endpoint.
4. Envie os arquivos para um repositório no GitHub:
   - `index.html`
   - `thanks.html`
   - `.nojekyll`
5. Ative o GitHub Pages:
   - *Settings → Pages → Source*: `Deploy from a branch`
   - *Branch*: `main` (ou `master`) / diretório `/ (root)`
6. Acesse a URL que o GitHub informar.

### Dicas
- Para sites de usuário/organização, use um repositório chamado `SEUUSUARIO.github.io`.
- Para sites de projeto, qualquer nome funciona (a URL será `SEUUSUARIO.github.io/NOME_DO_REPO`).
- Use `thanks.html` como página de redirecionamento pós-envio (opcional).

### Segurança
- Não inclua tokens/segredos no repositório.
- Ative HTTPS no Pages (Settings → Pages).

Boa publicação! 🚀
