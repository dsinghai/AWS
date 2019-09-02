Copy a file from local machine to AWS ec2 instance  using scp cmd.

aws ec2 describe-instance-status

$ aws ec2 describe-instances

$ aws ec2 start-instances --instance-ids i-1348636c

$ aws sns publish --topic-arn arn:aws:sns:us-east-1:546419318123:OperationsError --message "Script Failure"

$ aws sqs receive-message --queue-url https://queue.amazonaws.com/546419318123/Test

aws s3 and aws s3api have different commands and functionality

$ aws s3 mb s3://mybucket

$ aws s3 ls s3://mybucket
AVAILABLE COMMANDS
       o cp

       o ls

       o mb

       o mv

       o presign

       o rb

       o rm

       o sync

       o website


https://github.com/aws/aws-cli

Long polling helps reduce your cost of using Amazon SQS by reducing the number of empty responses. You can enable long polling using the AWS Management Console by setting a Receive Message Wait Time to a value greater than 0. See: https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-long-polling.html


When you stop an instance, AWS shut it down. AWS don't charge usage for a stopped instance, or data transfer fees, but do charge for the storage for any Amazon EBS volumes. See: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/Stop_Start.html

