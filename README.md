This repo contains a freshly generated Nx workspace created by choosing the following options in the creation process:

- workspace type: Integrated monorepo
- what to create: React monorepo
- bundler: Vite
- stylesheet format: Emotion
- enabled Nx Cloud

Running the e2e tests with `nx run nx-react-e2e-issue-e2e:e2e` works fine. The sample test passes.

Opening the Cypress UI with the `cypress:open` script (see `package.json`) and then opening the `app.cy.ts` spec file results in an infinite loop where Cypress tries to load the tests.
