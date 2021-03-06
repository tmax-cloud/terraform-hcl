# 테라폼 사용하기 - AWS Quickstart

## Prerequisite
* 필수 모듈  
  * [terraform v0.12.0](https://www.terraform.io/downloads)

## Step 1. AWS Credential 설정
* 'aws-provider.tf 에 access_key, secret_key 정보 입력'
* 해당 Credential 정보는 AWS의 IAM Management Console에서 확인 및 설정 가능


## Step 2. 테라폼 플랜 명령 실행
* AWS에 생성될 리소스 정보 확인
    ```bash
     $ terraform plan
    ```

## Step 3. 테라폼 어플라이 명령 실행
* AWS에 실제로 리소스 프로비저닝
    ```bash
     $ terraform apply
    ```

## Step 4. 테라폼 디스트로이 명령 실행
* AWS에 terraform을 통해 배포한 리소스 삭제
    ```bash
     $ terraform destroy
    ```
