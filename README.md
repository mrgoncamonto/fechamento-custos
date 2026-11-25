# Painel de Resultado da Engenharia

Endereço: https://fechamento-custos.netlify.app

Site estático (Netlify) + login e dados no Supabase (projeto "Fechamento de Custos" xklijhajhuzkhkymojai, tabelas painel_*).
O site não contém números: os dados só chegam depois do login, conforme o perfil (admin ou leitura).

## Atualizar a cada fechamento
1. Rodar o motor (RODAR_MOTOR.bat).
2. Rodar PUBLICAR.bat -> envia o mês ao Supabase. O site já mostra o mês novo. Sem deploy.
3. Commit + push só quando o visual do painel mudar (aí o Netlify faz 1 deploy).

## Usuários
- Quem pode ver: tabela painel_usuarios (login + perfil) e painel_dominios no Supabase.
- Criar acesso: Supabase > Authentication > Users > Invite user (ou Add user com senha provisória).
