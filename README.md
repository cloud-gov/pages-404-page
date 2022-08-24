## Pages 404 page

### About

[Cloud.gov Pages](https://github.com/cloud-gov/pages-core) helps federal agencies and offices quickly launch compliant websites.

This is the 404 error page for Pages *client sites*, as opposed to the Pages web app itself.

### Deployment

To deploy, copy the 404-pages-client.html to your S3 bucket root 404.html
```
aws s3 cp 404-pages-client.html s3://[BUCKET]/404.html
```
