# Using environment variables

Environment variables are extremely handy for setting sensitive information such as secret API keys.

They keep things out of source control and are used very frequently in CI/CD flows.

This lesson will teach you the basics of using environment variables in lambda functions.

## Steps

<!-- AUTO-GENERATED-CONTENT:START (GENERATE_LESSONS_STEPS)-->
 1. In `serverless.yml`, add an environment variable for all functions to access. http://bit.ly/2yVp4CR

 2. In `serverless.yml`, add an environment variable only `bar` function to access. http://bit.ly/2yVp4CR

 3. In `handler.js`, Grab the global env variable and return it in the foo function response

 4. In `handler.js`, Grab the env variable defined on bar function and return it in the bar function response

 5. After adding your environment variables to serverless.yml and handler.js.
Run `sls deploy` to deploy the service
<!-- AUTO-GENERATED-CONTENT:END -->