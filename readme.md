### About
This is an image processing app built with serverless framework. It takes an image from a url, download and resize on the fly and upload to an s3 bucket

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
