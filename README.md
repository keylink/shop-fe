S3 and CloudFront links
- [S3 Website](http://myshop-bucket.s3-website-eu-west-1.amazonaws.com/)
- [CloudFront S3 Website](https://d14k888n3xn2m2.cloudfront.net/)
- [CloudFront Serverless URL](https://d2z0j37xyzp4h.cloudfront.net/)

## Available Scripts
### `start`
Starts the project in dev mode with mocked API on local environment.
### `build`
Builds the project for production in `dist` folder.
### `preview`
Starts the project in production mode on local environment.
### `test`, `test:ui`, `test:coverage`
Runs tests in console, in browser or with coverage.
### `lint`, `prettier`
Runs linting and formatting for all files in `src` folder.
### `client:deploy`, `client:deploy:nc`
Deploy the project build from `dist` folder to configured in `serverless.yml` AWS S3 bucket with or without confirmation.
### `client:build:deploy`, `client:build:deploy:nc`
Combination of `build` and `client:deploy` commands with or without confirmation.
### `cloudfront:setup`
Deploy configured in `serverless.yml` stack via CloudFormation.
### `cloudfront:domainInfo`
Display cloudfront domain information in console.
### `cloudfront:invalidateCache`
Invalidate cloudfront cache.
### `cloudfront:build:deploy`, `cloudfront:build:deploy:nc`
Combination of `client:build:deploy` and `cloudfront:invalidateCache` commands with or without confirmation.
### `cloudfront:update:build:deploy`, `cloudfront:update:build:deploy:nc`
Combination of `cloudfront:setup` and `cloudfront:build:deploy` commands with or without confirmation.
### `serverless:remove`
Remove an entire stack configured in `serverless.yml` via CloudFormation.