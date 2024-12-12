# Currents Automation Rules with Playwright

Playwright [Automation Rules](https://docs.currents.dev/guides/automation-rules) for Currents.

This is a simple example Playwright test project, that shows the different ways to configure the Currents Playwright fixtures to apply Rule Automation.


## Setup

- Install dependencies with `npm install`
- Update `playwright.config.ts` with Currents [record key](https://docs.currents.dev/guides/record-key) and [project id](https://docs.currents.dev/dashboard/projects/project-settings)
- Run `npm run test` for running tests, behind the scenes:
  - runs playwright tests
  - applied automation rules during the run
  - sends results to the Currents dashboard
 
## Rules Creation

Rules are created in the Currents Dashboard (see https://docs.currents.dev/guides/automation-rules#creating-rules-in-currents for more info)

<img width="1306" alt="Screenshot 2024-12-10 at 3 22 45 PM" src="https://github.com/user-attachments/assets/d150c645-7b6d-448c-b1a8-31934cf0b460" />

<img width="873" alt="Screenshot 2024-12-10 at 3 27 00 PM" src="https://github.com/user-attachments/assets/75e1165c-f973-4d73-8056-db9dc2a1da4f" />

## Examples

- Run `npm run test:reporter` for using [`playwight test`](https://docs.currents.dev/getting-started/playwright/you-first-playwright-run#using-reporter-configuration) command with Currents loaded as a reporter
- Run `npm run test:pwc` for using [`pwc`](https://docs.currents.dev/getting-started/playwright/you-first-playwright-run#using-the-cli) command
- Run `npm run test:pwc-p` for [orchestrated](https://docs.currents.dev/guides/parallelization-guide/pw-parallelization/playwright-orchestration) runs

## Licence

MIT License
