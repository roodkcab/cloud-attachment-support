## Configuration
choose storage backend, i.e. Aliyun OSS or S3 Storage

### OSS
you can easily generate oss access key and access token with aliyun RAM system.
after create a account with token and secret, do not forget to grant read and write
permission of your oss bucket to this account.

finally, fill all of information requested by cloud-attachment like this below.

<img src="https://raw.githubusercontent.com/roodkcab/cloud-attachment-support/master/images/oss.png" width="800">

### S3
you can easily generate aws access key and access token with aws RAM system.
after create a account with token and secret, do not forget to grant read and write
permission of your s3 bucket to this account.

<img src="https://raw.githubusercontent.com/roodkcab/cloud-attachment-support/master/images/s3.png" width="800">

## Upload
once you finish up configuration, you can test it with simply click upload button in cloud-attach panel.

<img src="https://raw.githubusercontent.com/roodkcab/cloud-attachment-support/master/images/uploader.png" width="400">

the file should be uploaded to OSS or S3 bucket based on your configuration, and you should see something in your storage
dashboard like below.

<img src="https://raw.githubusercontent.com/roodkcab/cloud-attachment-support/master/images/s3_uploader.png" width="400">



## Download
