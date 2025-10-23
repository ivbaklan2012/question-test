# Serverless Version API

This project contains a serverless application that can be deployed with the SAM CLI.

The application uses several AWS resources, including Lambda functions and an API Gateway API. These resources are defined in the `template.yaml` file.

## Interview Task

The task is to implement a new API route `/version` that returns a JSON object containing the application's version.

**Requirements:**

1.  Create a new API Gateway route `/version` with a `GET` method.
2.  This route should be handled by a new or existing Lambda function.
3.  The Lambda function should read the `version` field from the `package.json` file located in the `hello-world/` directory.
4.  The API should return a JSON response in the format: `{"version": "X.Y.Z"}` where `X.Y.Z` is the version read from `package.json`.

## Resources

See the [AWS SAM developer guide](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html) for an introduction to SAM specification, the SAM CLI, and serverless application concepts.

You may use any other resource(s) in your aid.
