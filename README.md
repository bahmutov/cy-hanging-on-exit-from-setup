# cy-hanging-on-exit-from-setup
> Example of Cypress v12 hanging if the setupNodeEvents calls process.exit(0)

If [cypress.config.js](./cypress.config.js) calls `process.exit` from the `setupNodeEvents` callback, Cypress hangs
