# Continuous Integration - GitHub actions VS AWS

## Create AWS CodePipeline

We'll create an AWS CodePipeline for `continous integration` for a python application we have.
Our code repository is GitHub and AWS CodePipeline will orchestrate the flow where anything changes.
- Go to AWS Management Console & find AWS CodePipeline.
- `Create new pipeline`
- Name the pipeline
- Select the pipeline type (V1 or V2)
- Select execution mode
- You only need to create a service role the first time you create a pipeline in CodePipeline.
- select `Source provider` as GitHub & connect