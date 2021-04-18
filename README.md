# Checkov for Terraform in Azure DevOps

This repository contains code to use Checkov for your Terraform configuration in a CI/CD pipeline in Azure DevOps.

You'll find two YAML files in which both give you the same result but one publishes the results for Checkov into your pipeline as a test result. In that way you have a nice graphical overview within your pipeline where you can see what checks have passed, failed or have been skipped.

`checkov.yml`: Publishes the results within the pipelines terminal.

`checkov-publishresults.yml`: Publishes the results into test results in your Azure DevOps pipeline.