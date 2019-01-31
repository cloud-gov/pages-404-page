## Federalist 404 page

### About

[Federalist](https://github.com/18F/federalist) helps federal agencies and offices quickly launch compliant websites.

This is the 404 error page for Federalist *client sites*, as opposed to the Federalist web app itself.

### Deployment

To deploy the 404 page, copy the 404-federalist-client.html to your S3 bucket root 404.html
```aws s3 cp 404-federalist-client.html s3://[BUCKET]/404.html```
