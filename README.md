# PHP Test Applications

A collection of applications used for testing the PHP buildpack

## Applications

| Name | Description
| ---- | -----------
| `php-info` | CloudFoundry PHP example application: phpinfo

### Output Content

All applications support the following REST operations:

| URI | Description
| --- | -----------
| `GET /` | The health of the application

## Deploying to Cloud Foundry

Each test application contains a `manifest.yml` file which allows the built application to be deployed to Cloud Foundry by simply issuing:

```
cf push
```
