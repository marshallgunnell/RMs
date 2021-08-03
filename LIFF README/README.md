# Overview

This is the demo app source code for the [Membership Card](https://lineapiusecase.com/en/api/miniliff.html) provided on the [LINE API Use Case site](https://lineapiusecase.com/en/top.html). By referring to the steps described in this article, you can develop a business card app using the LIFF. LIFF allows you to get user IDs to distinguish users, and arbitrary display names that users have registered.

The source code environment introduced on this page uses AWS.

# Libraries

## Python

Install Python version 3.8 or later if it isn't already installed.

You can check if it's installed by entering this command in Command Prompt or Terminal:

```
python --version
```

If Python is installed, the version will be returned. For example:

```
Python 3.8.3
```

Install Python (3.8 or higher), used for back-end development, in your local development environment if it's not already installed.

Python installation reference site:

Windows: https://docs.python.org/3/using/windows.html
Mac: https://docs.python.org/3/using/mac.html

## AWS SAM

The AWS Serverless Application Model (AWS SAM) is used to deploy this app.

See the [official AWS documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html) to register and set up an AWS account, and install the AWS SAM CLI and Docker.

*Recommended version of SAM CLI is 1.15.0 or later.
*Docker installation is also required, with or without local testing.

### Reference points in the official documentation

Complete these items in the official documentation and proceed to the next step. If you have already installed it, you can skip this section.

*This document was created in December 2020 and may be inconsistent with the latest official documentation.

1. Install AWS SAM CLI
1. Set up AWS authentication credentials
1. (Optional) Tutorial: Deploying the Hello World app

# Getting Started / Tutorial

In this section, you'll learn how to create a LINE channel, build the back-end and front-end, submit test data, and operation verification, required for app development.

See these steps to build the production environment (AWS) and the local environment:

- **[Create a LINE channel](./docs/liff-channel-create.md)**
- **[Build the back-end](./docs/back-end-construction.md)**
- **[Build the front-end](./docs/front-end-construction.md)**
***
- **[Check operation](./docs/validation.md)**
***

# License

All files on BusinessCard are free to use without conditions.

Download and clone to start developing apps using LINE API.

See [LICENSE](LICENSE) for details. (English)

# How to contribute

Thank you for taking the time to contribute. LINE API Use Case Hair Salon isn't different from any other open source projects. You can help by:

- Filing an issue in [the issue tracker](https://github.com/line/line-api-use-case-liff/issues) to report bugs and propose new features and improvements.
- Asking a question using [the issue tracker](https://github.com/line/line-api-use-case-liff/issues).
- Contributing your work by submitting [a pull request](https://github.com/line/line-api-use-case-liff/pulls).

When you are sending a pull request, be aware of and accepting the following:

- Grant [the same license](LICENSE) to the contribution
- Represent the contribution is your own creation
- Not expected to give support for your contribution
