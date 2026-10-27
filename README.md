# Caixa de entrada Sandstride

Site estático (sem build) que reúne as conversas dos marketplaces. Backend: Supabase `Chats-Sandstride`.

## Publicar na Vercel
1. Importe este repositório na Vercel (Framework: Other, sem comando de build, pasta raiz `/`).
2. Copie a URL gerada (ex.: https://sandstride-chat.vercel.app).
3. No Supabase: Authentication → URL Configuration → Site URL = essa URL e adicione-a em Redirect URLs.
4. Entre com "Esqueci a senha" para criar a senha do primeiro administrador.

A chave em `js/config.js` é a chave pública (publishable); a segurança vem das regras (RLS) no banco.
