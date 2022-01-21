# AWS learning
## Powerful tool: 
1. AWS cloudshell: aws s3 help, aws s3 ls(show the bucket in the system)
2. Cloud 9: avoid api key(role based)

删除当前目录下的所有__pycache__子目录

find . -name '__pycache__' -type d -exec rm -rf {} \;
1
删除当前目录下所有.pyc文件

find . -name "*.pyc"  | xargs rm -f

rm -rf .git

docker container, image remove