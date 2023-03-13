# devops_on_aws

Follow the steps to create a CI/CD pipeline in AWS

- Use code build

      -  provide a name to the project
      -  select either codecommit or github as source
      -  enter repo name
      -  create a new role
      -  select os either linux image2 or ubuntu
      -  the codebase should have a buildspec file
      -  add artifacts if any
- Use code pipeline
   
      - click on create pipeline
      - give a name to your pipeline
      - give a role to your pipeline
      - in the advanced settings select default location
      - provide a source may be github/codecommit
      - add build stage
             - select build provider either codebuild or jenkins
             - select project from codebuild
      - add deploy stage
      

