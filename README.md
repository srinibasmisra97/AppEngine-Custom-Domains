# Custom Domains with App Engine Services

The article to setup custom domains can be found here.

**Note:** This repo contains the sample code that can be used to deploy multiple services to App Engine.

To create the App Engine App (if not created already):
```bash
gcloud app create --project=[YOUR_PROJECT_ID]
```

Now we can deploy all the sample apps in this repository:
```bash
cd AppEngine-Custom-Domains
gcloud app deploy default/app.yaml
gcloud app deploy golang/app.yaml
gcloud app deploy java/app.yaml
gcloud app deploy nodejs/app.yaml
gcloud app deploy php/app.yaml
```