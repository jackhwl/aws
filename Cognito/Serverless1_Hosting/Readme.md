1. Hosting web applications with amazon s3
  - Understanding hosting needs
  - Uploading a react app to amazon s3
    - build react app
    - create bucket in s3
  - Hosting a React App in amazon s3
  - Amazon s3 hosting performance
    - https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect
    - Add Metadata to js: System defined, cache-control max-age=31536000, public
    - Configuring Cache Headers using the AWS CLI
      - JS/CSS file 1 year
      - aws s3 cp \
          s3://vi-serverless-hosting/ s3://vi-serverless-hosting/ \
          --exclude '*' \
          --include '*.css' --include '*.js' \
          --cache-control 'max-age=31104000, public' \
          --recursive \
          --metadata-directive REPLACE --acl public-read
      - images 1 week
      - aws s3 cp \
          s3://vi-serverless-hosting/ s3://vi-serverless-hosting/ \
          --exclude '*' \
          --include '*.jpg' --include '*.png'  --include '*.gif'\
          --cache-control 'max-age=604800, public' \
          --recursive \
          --metadata-directive REPLACE --acl public-read
2. Utilzing amaxon cloudfront
  - amazon cloudfront overview