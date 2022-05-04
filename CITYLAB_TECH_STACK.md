# CityLab Tech Stack
Our Workflow is centered around Javascript and ([Typescript](https://www.typescriptlang.org/)). This doesn't mean, that we reject other programming languages.

- Our favoured view-library is **[React](https://reactjs.org/)**, however we are as well interested about **[SolidJs](https://www.solidjs.com/)**.
- Our go-to App Framework is **[NextJs](https://nextjs.org/)** (Good implementaiton of SSG, iSSG, SSR and Client Side), yet we are also interested about newer kids on the block such as **[Redwood](https://redwoodjs.com/)** and **[Remix](https://remix.run/)**.
- For static sites, we like to work with **vanilla HTML** or **[eleventy](https://www.11ty.dev/)**. We are also keen on working with **[Astro](https://astro.build/)**.
- Our favourite CSS solution is **[Tailwind.css](https://tailwindcss.com/)**. In some rare cases we work with **vanilla CSS**, **[Styled Components](https://styled-components.com/)** or **[CSS modules](https://github.com/css-modules/css-modules)**.
- Our favoured auth-solution is **[Supabase](https://supabase.com/)**.
- Our go-to relational database is **[Postgres](https://www.postgresql.org/)**, when possible in context of **[Supabase](https://supabase.com/)**
- Our preferred cache solution is **[Redis](https://redis.io/)**
- We **avoid** working with NoSQL Database ([Redis](https://redis.io/))
- Our favourite API-building solution is **[Fastify](https://www.fastify.io/)**
- We manage our **[NodeJS](https://nodejs.org/en/)** versions with **[NVM](https://github.com/nvm-sh/nvm)**. We rely on the long-term-support (LTS) version per default. On a pre-project-basis, we use other NodeJS versions, which we define in a `.nvmrc` file. However we only allow stable versions. This means only even version numbers. See [https://nodejs.org/en/about/releases/](https://nodejs.org/en/about/releases/)
- As state management solution in our React Apps we use **[react hooks](https://reactjs.org/docs/hooks-intro.html)** (as local as possible) and **[react context](https://uk.reactjs.org/docs/context.html)** for more global state and/or when using local hooks is not enough.
- To ensure a high code-quality, We use:
    - **[Eslint](https://eslint.org/)** & **[Prettier](https://prettier.io/)** & **[Typescript](https://www.typescriptlang.org/)** (We are also curious about the [Rome toolchain](https://rome.tools/))
    - **[Github Actions](https://github.com/features/actions)**
    - Testing
        - **[Jest](https://jestjs.io/)** for unit/integration testing
        - **[Playright](https://playwright.dev/)** (preferred) or **[Cypress](https://www.cypress.io/)** for end-to-end tests
        - **[Storybook](https://storybook.js.org/)** for component testing in isolation
- We use the following deployment services: **[Vercel](https://vercel.com)**, **[Render](https://render.com/)** or **[Netlify](https://www.netlify.com/)**. We also tried [**fly.io**](http://fly.io) a few times and quite liked it.
