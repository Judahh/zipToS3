# zipToS3
Zip a NODE/NEXT project and publish a zip file to S3
inputs:
  folder:  # folder name
    description: 'Folder Name'
    required: true
    default: 'production'
  aws_key_id:
    description: 'AWS Key ID'
    required: true
  aws_key:
    description: 'AWS Key'
    required: true
  aws_bucket:
    description: 'AWS Bucket'
    required: true