This is a simple action that lets you put all the files of your repo to a folder, zip that folder and upload the folder to amazon s3 bucket when you push a new tag to github.

You can configure every settings according to your needs. Simply copy the code in action.yml file, put it in .github/workflows/main.yml file.

You need to store the credentials as secrets.
1. AWS_ACCESS_KEY_ID
2. AWS_SECRET_ACCESS_KEY
3. AWS_REGION
4. S3_BUCKET_NAME

All the secret names are self explanatory, you can find those from your s3 panel.

Don't forget to replace your-zip-file-name.zip and your-directory-name with your preferred ones.

More details will be added soon.