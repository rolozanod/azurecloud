[![Azure CI](https://github.com/rolozanod/azurecloud/actions/workflows/main.yml/badge.svg)](https://github.com/rolozanod/azurecloud/actions/workflows/main.yml)
[![AWS CI](https://github.com/rolozanod/azurecloud/actions/workflows/main_aws.yml/badge.svg)](https://github.com/rolozanod/azurecloud/actions/workflows/main_aws.yml)

# Multicloud integration

1. Started the task by downloading the [sample code](https://github.com/noahgift/github-actions-demo) from [Noah's repo](https://github.com/noahgift).
2. Created a repo on [my GitHub account](https://github.com/rolozanod) to host the sample code.
3. Started with the Azure CI because it is tha one that is not included in the sample code.
  1. Opened the shell
  2. Set up the ssh pairs with GitHub
  3. Clone the repo
  4. Copied the requirements.txt and created the requierements-az.txt that includes the packages to use in Azure (added black to format the code)
  5. Pushed the code back to GitHub
  6. Created the yaml file in GitHub Actions to perform CI
  7. Added the status badge to the Github README file
