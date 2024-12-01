_**IMPORTANT NOTE:**_ moved to https://github.com/ebi-yade/app-engine-samples/tree/main/default-deny

# app-engine-default-deny
The easiest way to deny access to the default service of App Engine

## About

This is the solution when you come across an error like the one below and if you do not intend to accept requests to the `default` service.

> ERROR: (gcloud.app.deploy) INVALID_ARGUMENT: The first service (module) you upload to a new application must be the 'default' service (module). Please upload a version of the 'default' service (module) before uploading a version for the 'api' service (module). See the documentation for more information. Python: (https://developers.google.com/appengine/docs/python/modules/#Python_Uploading%%20modules) Java: (https://developers.google.com/appengine/docs/java/modules/#Java_Uploading%%20modules)

## Usage

Simply run:

```sh
gcloud app deploy --version deny
```

## Contribution

For simplicity, no additional features are planned.

However, we appreciate any suggestions to make the project brighter. 🙌
