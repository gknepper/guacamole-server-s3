# guacamole-server-s3
guacamole-server with a S3 bucket mounted internally to save the recordings 


All the changes were made on Dockerfile_S3 only. The code base is guacamole-server 1.5.5. 

## Build

`docker build -t guacamole/guacd-s3:1.5.5 -f Dockerfile_S3 .`


## Use

Overwrite the variable: `MOUNT_S3_PARAMETERS` with the parameter from https://github.com/awslabs/mountpoint-s3


