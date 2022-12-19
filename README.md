# ts-in-theme-repro
Using node v18.10.0

1. Run `yarn`
2. Run `yarn workspace example-site develop`
3. Expected result: 2 logs on build startup - one for js and one for ts. Actual result: just 1 log for JS plugin.