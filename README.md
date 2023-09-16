# Simple recipe site 

For our home recipes to save on printing paper. Hosted on an AWS S3 bucket annd using GitHub actions to build (and so test) the site then send to S3 and invalidate the CloudFront cache.

## Build the docs with

`sphinx-build source/ build/ -a`

## Create a Pull Request and GH Actions will publish to the S3 bucket
