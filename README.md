Estrutura

comunidade-app-frontend/
├─ src/
│  ├─ pages/
│  │  ├─ Home.tsx
│  │  ├─ Groups.tsx
│  │  ├─ GroupDetail/
│  │  │  ├─ Chat.tsx
│  │  │  ├─ Info.tsx
│  │  │  └─ Events.tsx
│  │  ├─ Rules.tsx
│  │  └─ Profile.tsx
│  ├─ components/
│  │  ├─ EventAlert.tsx
│  │  ├─ BannerGlobal.tsx
│  │  └─ BannerGroup.tsx
│  ├─ services/
│  │  └─ supabase.ts
│  └─ main.tsx
├─ public/
│  └─ manifest.json
├─ README.md



Conteúdo do README.md (frontend) 

# Frontend – Plataforma de Comunidades

Aplicativo web (PWA) para:
- acesso a grupos temáticos
- chat em tempo real
- avisos de encontros
- leitura de informações relevantes

## Princípios de UX
- chat é temporário
- informação relevante é persistente
- eventos sempre destacados
- publicidade é discreta e controlada

## Stack
- React + Vite + TypeScript
- Supabase Client
- Deploy em Vercel


Commits do frontend (na ordem)
- feat: estrutura inicial do app (vite + pwa)
feat: telas institucionais e regras
feat: autenticação e proteção de rotas
feat: listagem e busca de grupos
feat: página de grupo com abas
feat: chat em tempo real
feat: aba de informações do grupo
feat: aba de eventos do grupo
feat: alerta de evento futuro na entrada do grupo
feat: banners globais e por grupo
feat: ajustes finais de ux
