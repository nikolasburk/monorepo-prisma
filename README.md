# Monorepo Prisma example

The goal of this example to show a simple monorepo setup with Prisma. The `PrismaClient` instance is created in the `prisma-db` package and can be accessed by other packages in the monorepo.

## Usage

```
git clone git@github.com:nikolasburk/monorepo-prisma.git
cd monorepo-prisma
yarn
yarn server:dev
```