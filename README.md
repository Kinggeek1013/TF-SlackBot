docker run \
-e ENVIRONMENT="test" \
-e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID \
-e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY \
-e AWS_DEFAULT_REGION="us-east-2" \
-v $(pwd):/opt/bitops_deployment \
bitovi/bitops:latest
