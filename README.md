# Xmodder Site Package

Arquivos prontos para hospedar seu site no GitHub Pages ou Netlify.

## Conteúdo
- `index.html` — página principal já com o link do Roblox (share code) configurado.
- `README.md` — este arquivo com instruções rápidas.

## Enviar para GitHub Pages (via navegador - mais simples)
1. Crie um repositório novo no GitHub (público). Ex.: `xmodder-site`.
2. Acesse o repositório e clique em **Add file → Upload files**.
3. Arraste os arquivos deste pacote (`index.html` e `README.md`) e clique em **Commit changes**.
4. Vá em **Settings → Pages** (ou `Code and automation → Pages`) e, em **Source**, escolha `main` e `/ (root)`. Salve.
5. Aguarde alguns segundos/minutos. O GitHub Pages irá fornecer o link: `https://SEU_USUARIO.github.io/SEU_REPO/`

## Enviar via Git (exemplo)
Substitua `SEU_USUARIO` e `SEU_REPO` pelos seus dados:
```bash
git init
git add index.html README.md
git commit -m "Add site"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

## Dicas
- Para acelerar indexação no Google, adicione o site ao Google Search Console e peça indexação.
- Se quiser que eu gere o `Script.lua` (para usar dentro do Roblox executor) com esse link ou preparar `siteLink` apontando para o GitHub Pages, me avisa e eu incluo aqui também.
- Eu não tenho acesso ao seu GitHub — você precisa fazer o upload/push com sua conta. Estou entregando tudo pronto para você só subir.
