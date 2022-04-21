# aws-gohugo-ci-cd-codepipeline

This cloudformation templates deploys an AWS Codepipeline with :
* codecommit as source stage
* codebuild as build stage with a GoHugo build script
* A S3 deploy stage

Prrequisites:
* an existing AWS S3 bucket
* an existing codecommit repositery
