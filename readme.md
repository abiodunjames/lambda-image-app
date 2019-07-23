### About
This is an image processing app built with serverless framework. It takes an image from a url, download and resize on the fly and upload to an s3 bucket

### Purpose
It was written to guide developers who want to get started using AWS Lambda.
Read the article here https://stackify.com/aws-lambda-with-node-js-a-complete-getting-started-guide/

### Install npm packages

```bash
 npm Install

```

```bash
$ serverless deploy
```

 With aws profile

```bash
serverless deploy --aws-profile profileName

```

### Invoking the function

```bash
curl -H "Content-type: application/json" -d '{"photoUrl":"https://www.petmd.com/sites/default/files/what-does-it-mean-when-cat-wags-tail.jpg"}' 'your-serverless-app-endpoint'

```
