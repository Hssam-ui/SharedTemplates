# Introduction 
This Repository contains general templates to be used in different solutions. The goal is to standardize the automated steps to build and deploy solution and have a minimaum of setup needed by each developer.

# Current state
- dotnet core template that build, test and publish the artifact to azure devops.
- python core template that build, test, scan and publish a docker image to the specified docker registry. This should be setup in the pipeline variables on azure devops.
