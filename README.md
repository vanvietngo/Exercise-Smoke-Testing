aws cloudformation deploy \
--template-file cloudfront.yml \
--stack-name production-distro-4 \
--parameter-overrides PipelineID=s3-16-6 \
--role-arn arn:aws:iam::874529357876:role/cloudformation-role
