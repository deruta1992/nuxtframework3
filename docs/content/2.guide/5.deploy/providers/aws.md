---
icon: IconCloud
---

# AWS

There's some options to host your app in AWS.
- Amplify ( S3 + Cloudfront ) 
  In this method, SSR is not available.
  Please write your server logic separately in lambda + API gateway

## How to Deploy in AWS Amplify
- RUN `` amplify configure project `` in your project root directory.
- Please type `` .output/public `` if asked "Distribution Directory Path".
- `` amplify publish `` command will host your app to S3.

## Deploy to Lambda?

Need help for How to deploy Nuxt to [AWS Lambda](https://aws.amazon.com/lambda/)?
Please read related articles on nitro.unjs.io.

:ReadMore{link="https://nitro.unjs.io/deploy/providers/aws.html" title="the Nitro documentation for AWS deployment"}
