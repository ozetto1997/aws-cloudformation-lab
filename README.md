AWSTemplateFormatVersion: '2010-09-09'
Description: "Exemplo simples - Criando um bucket S3 com CloudFormation"

Resources:
  MeuBucketS3:
    Type: AWS::S3::Bucket
    Properties:
      BucketName: meu-primeiro-bucket-exemplo-123
