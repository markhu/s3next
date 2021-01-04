# s3next

CICD a Next.JS web app via GitHub actions

Continuously deploy updates a'la the article at [How to Use Github Actions to Deploy a Next.js Website to AWS S3](https://www.freecodecamp.org/news/how-to-use-github-actions-to-deploy-a-next-js-website-to-aws-s3/)

## Initial Goals

1. auth with AWS Cognito
2. read metadata from Cognito
    1. display formatted metadata
3. cache results in S3

## Next Goals

1. read metadata from external API
2. perform other Cognito actions as allowed by role permissions
3. handle exceptions
