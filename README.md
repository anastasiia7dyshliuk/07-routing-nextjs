# NoteHub — 07-routing-nextjs

Домашня робота 07: маршрутизація в Next.js (App Router).

- Сторінка 404 (`app/not-found.tsx`)
- Фільтрація нотаток за тегом: паралельний маршрут `@sidebar` + catch-all `app/notes/filter/[...slug]`
- Модальне вікно з деталями нотатки: паралельний маршрут `@modal` + перехоплення `(.)notes/[id]`
- TanStack Query, axios, CSS Modules, TypeScript

## Запуск

```bash
npm install
# .env.local
# NEXT_PUBLIC_NOTEHUB_TOKEN=<ваш токен>
npm run dev
```

На Vercel додайте змінну оточення `NEXT_PUBLIC_NOTEHUB_TOKEN`.
