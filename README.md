# Site SegPrevent Assessoria

Site institucional da SegPrevent Assessoria — consultoria em Saúde e Segurança do Trabalho.

## Como publicar no GitHub Pages (grátis)

1. Crie uma conta em github.com (se ainda não tiver).
2. Clique em **New repository**.
   - Repository name: `segprevent-site`
   - Marque **Public**
   - Clique em **Create repository**
3. Na página do repositório, clique em **uploading an existing file**.
4. Arraste TODOS os arquivos desta pasta (`index.html`, `image-slot.js`, `.nojekyll` e a pasta `src`) para a área de upload.
   - Importante: mantenha a pasta `src` com os arquivos dentro dela.
5. Clique em **Commit changes**.
6. Vá em **Settings** (menu do repositório) → **Pages** (menu lateral).
7. Em **Source**, selecione **Deploy from a branch**.
8. Em **Branch**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
9. Aguarde 1 a 2 minutos. O endereço do site aparecerá no topo da mesma página, no formato:
   `https://SEU-USUARIO.github.io/segprevent-site/`

## Formulário de contato

O formulário usa o Formspree (plano gratuito, 50 envios/mês).
As solicitações chegam no e-mail cadastrado na conta do Formspree.

Endpoint configurado: `https://formspree.io/f/xrpgznna`

Se precisar trocar, edite o arquivo `src/sections.jsx` e busque por `formspree.io`.

## Domínio próprio (opcional)

Para usar `www.segpreventassessoria.com.br` no lugar do endereço do GitHub:

1. Em **Settings → Pages → Custom domain**, digite seu domínio e salve.
2. No painel do seu registrador de domínio, crie um registro CNAME apontando
   `www` para `SEU-USUARIO.github.io`.

## Estrutura dos arquivos

- `index.html` — página principal
- `src/styles.css` — todo o visual do site
- `src/components.jsx` — menu de navegação e rodapé
- `src/sections.jsx` — seções (hero, sobre, treinamentos, produtos, parceiros, contato)
- `src/app.jsx` — montagem da página e botão flutuante do WhatsApp
- `src/logo-data.js` — logo embutida
- `src/photos-data.js` — fotos embutidas
- `image-slot.js` — componente de imagem
- `.nojekyll` — necessário para o GitHub Pages servir os arquivos corretamente
