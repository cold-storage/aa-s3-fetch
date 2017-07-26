# AA S3 File Fetcher

Usage: aa-s3-fetch SPEC_FILE [OUTPUT_FOLDER]

Gets files from Amazon S3.

SPEC_FILE is a CSV file like so.

    "Cloud Documents: Cloud Documents Name","Folder Id"
    "My Alias Filename1.png","some/not/so/friendly/path/on/s3-a.PNG"
    "My Alias Filename2.png","some/not/so/friendly/path/on/s3-b.PNG"

OUTPUT_FOLDER defaults to 'out'

Make sure you have a credentials file like so.

    [default]
    aws_access_key_id = your_access_key
    aws_secret_access_key = your_secret_key

The credentials file should be located like so.

    Mac/Linux:  ~/.aws/credentials
    Windows:    C:\\Users\\USERNAME\\.aws\\credentials
