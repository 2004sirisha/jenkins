@Library("my-shared-library") _

environment {
  BRANCH="master"
  PROJECT_NAME="myproject"
  BASE_URL="https://gitbucket.com/"
}
echo "Debug: BRANCH = ${env.BRANCH}, PROJECT_NAME = ${env.PROJECT_NAME}, BASE_URL = ${env.BASE_URL}"
arjun(branch_name: env.BRANCH,
     project_name: env.PROJECT_NAME,
     base_url: env.BASE_URL
     )
