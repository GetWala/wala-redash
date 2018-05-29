### What is used for

This is CloudFormation template to get a redash (https://redash.io/) environment up and running. 

The CF template is deployed using the Serverless framework that passes parameters into templates and allows passing or parameters and deployments to mutlitple environments.

### Requirements before use:

1. Setup ssm parameters for in your AWS ACCOUNT for the following 
    - aws-account-number
    -   postgres-password
2. Change the template to use your parameter names under the profiles section of the `serverless.yaml` file

3. Update the `package.json` scripts to use your AWS_PROFILE name.

### How to use:

```
yarn deploy-sandbox
```
OR

```
npm run deploy-sandbox
```
* Add attional scripts as needed per stage and AWS environment- Add attional scripts as needed per stage and AWS environment *
