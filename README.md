# S3 Bucket Encryptor

S3 Bucket Encryptor는 S3 Bucket에 Server Side Encryption을 적용하기 이전에 업로드 된 Objects에 암호화(AES256) 설정을 일괄 적용해주기 위해 작성된 프로그램입니다.


## 🍽Prerequistes
1. Python 3.7+
2. AWS CLI configuration - S3 Object 변경을 위해 Local 환경에 저장되어 있는 AWS credentials를 이용합니다. https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html


## 설치
~~~
pip3 install s3bucketencryptor
~~~


## 👟 실행 방법

~~~
s3enc
  --bucket "NAME OF BUCKET" (required)
  --prefix "PREFIX YOU WANT TO ECRYPT" (required)
  --profile "AWS PROFILE CONFIGURED"
  --region "AWS REGION WHERE THE BUCKET EXISTS"
~~~
