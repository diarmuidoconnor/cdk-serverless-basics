

aws lambda list-functions

  aws lambda invoke --function-name  SimpleAppStack-SimpleFn7D0601E0-4bL6BVRdOm2M \
       --cli-binary-format raw-in-base64-out   \
       --payload '{ "key": "value" }' \
       response.json 