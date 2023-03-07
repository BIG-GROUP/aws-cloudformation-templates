#ARCHITECT DESIGNER  : 
https://ap-southeast-3.console.aws.amazon.com/cloudformation/designer

atau

# Create Stack Using Cloudformation Service in AWS Command Line Interface
aws cloudformation create-stack --stack-name MasjidBucketPolicyStack-03072023 --template-body file://masjid.bucket-policy.yaml --parameters ParameterKey=BucketName,ParameterValue=MasjidS3Bucket ParameterKey=PublisherAccountID,ParameterValue=123456789012

