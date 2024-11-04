This is a simple example of how to use [Next-Auth v5](https://authjs.dev/getting-started/migrating-to-v5)

To use it:

1. ```git clone https://github.com/galsever/next-auth-simple-ex.git```
2. cp .env.example .env.local
3. Set the env vars
4. Then run:
````shell
bun i
````
````shell
bun dev
````

These files serve for authentication:
- auth.ts
- auth.config.ts
- middleware.ts
- prisma.ts
- prisma/schema.prisma

The Google & Nodemailer Provider are split on purpose, because otherwise next-auth doesn't work