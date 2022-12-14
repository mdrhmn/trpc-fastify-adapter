# trpc-fastify-adapter
Sandbox repository for testing tRPC integration with Fastify for VaaS PoC.

## Set Up

1. Install dependencies in `package.json`
2. Run `npm start`
3. Test endpoints:
   - GET `http://localhost:3000/trpc/getUserById?input=INPUT`
   - POST `http://localhost:3000/trpc/createUser`
     - Body: `'name', 'bio'`

## References

[Usage with Fastify](https://trpc.io/docs/fastify)