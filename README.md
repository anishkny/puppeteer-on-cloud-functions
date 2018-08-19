Google Cloud Function to take a screenshot of specified URL

Based on this blog post: *[Introducing headless Chrome support in Cloud Functions and App Engine](https://cloud.google.com/blog/products/gcp/introducing-headless-chrome-support-in-cloud-functions-and-app-engine)*

## Deployment
```
gcloud beta functions deploy screenshot --trigger-http --runtime nodejs8 --memory 1024MB
```
