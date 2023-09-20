## Next.js 13/App Router app.

### Стек технологий:
- NextJS App Router
- TypeScript
- TailwindCSS
- Zustand as state manager
- shadcn for ui kit
- Clerk for authentication
- PlanetScale for DB
- Prisma ORM
- uploadthing for files
- LiveKit for video chat
- socket.io
- React-hook-form

### Требования

**Node version 18.x.x**

### .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=


DATABASE_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_URL=
```

### Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```
