# DM Field BAND TO GO

Aplicativo comercial completo, com carteira de clientes, roteiros, atendimento, positivação, BAND TO GO e Projeto 24 Horas.

## Publicar no GitHub Pages
1. Abra o repositório `Central-de-Projetos-`.
2. Remova ou substitua os arquivos antigos da raiz.
3. Envie **todos os arquivos deste pacote para a raiz**, sem a pasta externa.
4. Em Settings > Pages, selecione Deploy from a branch, `main`, `/ (root)` e Save.
5. Acesse `https://andrerepolicomercial-star.github.io/Central-de-Projetos-/`.

## Atenção aos registros
Os atendimentos são armazenados no `localStorage` do navegador/dispositivo, e não sincronizados com o GitHub. Antes de limpar dados do navegador, mudar de aparelho ou trocar de domínio, exporte um backup JSON pelo aplicativo. A publicação não transfere automaticamente registros existentes de outro navegador ou endereço.

## Atualização
O service worker usa atualização pela rede para páginas HTML, para evitar que versões antigas fiquem presas no cache.
