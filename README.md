# Mocca Vendas

Site de vendas da Mocca Studio (impressão 3D).

- `public/` — o site (index.html e fotos)
- Dados e logins: Supabase, projeto `mocca-vendas`
- Publicação: Cloudflare Worker `moccavendas` (https://moccavendas.guihriot.workers.dev), que publica sozinho a cada envio para a branch `main`
