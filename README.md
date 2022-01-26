# zipToS3

inputs:
  folder:  # folder name
    description: 'Folder Name'
    required: true
    default: 'production'
  aws_key_id:
    description: 'AWS Key ID'
    required: true
    default:  ${{ secrets.AWS_KEY_ID }}
  aws_key:
    description: 'AWS Key'
    required: true
    default:  ${{ secrets.AWS_KEY }}
  aws_bucket:
    description: 'AWS Bucket'
    required: true
    default:  ${{ secrets.AWS_BUCKET }}