# Prisma-S3-Backup (as a Github action)

## Instructions

- Download repo locally
- Create an AWS account
- Create AWS credentials (ACCESS ID/SECRET)
- Create an S3 Bucket

Add following secrets to github

```bash
PRISMA_ENDPOINT=''
PRISMA_SECRET='' # Optional if your database is not protected by a secret
AWS_ACCESS_ID=""
AWS_ACCESS_SECRET=""
AWS_BUCKET_NAME=''
```

If all has been setup successfully script should export prisma db and upload to S3 every hour.
