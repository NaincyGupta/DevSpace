# DevSpace

The website being described is a social network for developers called DevSpace. 

# Quick Start 🚀

### Add a default.json file in config folder with the following

```json
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```


### Test website before deploying

Check in browser on [http://localhost:5000/](http://localhost:5000/)

### Deploy to AWS EC2 and store files at S3 Bucket

AWS EC2 instance is created and is live on ->
Instance: i-083e53963050b7cb4 (mydevserver)
Public IP address : 3.19.211.110

AWS S3 bucket info -> 
Amazon Resource Name (ARN): arn:aws:s3:::developerspace


## App Info

### Author

Naincy Gupta & Harita Trivedi
