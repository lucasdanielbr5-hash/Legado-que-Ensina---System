# Legado Que Ensina — React + Vite + Tailwind + Supabase

Recriação limpa do sistema de gestão psicopedagógica, sem a sobreposição de camadas do HTML legado.

## Stack

- React 19 + TypeScript
- Vite 8
- Tailwind CSS 4 via plugin oficial do Vite
- Supabase JS 2
- React Router
- TanStack Query
- Zustand
- React Hook Form + Zod
- Recharts
- Lucide React

## Desenvolvimento

```bash
npm install
cp .env.example .env.local
npm run dev
```

Preencha `VITE_SUPABASE_URL` e `VITE_SUPABASE_ANON_KEY` com as credenciais públicas do projeto Supabase.

## Produção

```bash
npm run typecheck
npm run build
npm run preview
```

O projeto já inclui `vercel.json` para SPA routing.

## Banco

Execute `supabase/migrations/0001_legado_schema.sql` no SQL Editor do Supabase. As políticas RLS devem ser mantidas em produção; nunca coloque a service role key no frontend.

## Padrão visual

A interface foi refeita em uma única linguagem visual azul-marinho, com Manrope, bordas discretas, botões azuis, alto contraste e breakpoints para desktop, tablet e celular.
