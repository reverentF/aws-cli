# Docker for aws-cli

https://hub.docker.com/r/reverentf/aws-cli

## How To Use
```
export AWS_ACCESS_KEY_ID="AAAAAAAA"
export AWS_SECRET_ACCESS_KEY="BBBBBBBB"
export AWS_DEFAULT_REGION="CCCCCCCCC"

docker run --rm \
    -e "AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID" \
    -e "AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY" \
    -e "AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION" \
    reverentf/aws-cli s3 ls
```
