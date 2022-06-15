
-- RUN cloudfront.yml file
```sh
aws cloudformation deploy --template-file cloudfront.yml --stack-name production-distro --parameter-overrides PipelineID="<s3bucketName>" --tags project=<yourTagName>
```