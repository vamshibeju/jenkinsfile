pipeline{
agent any
stages{
stage('branchparameter'){
steps{
  script{
    //def branch= "{GIT_BRANCH.replace("origin/","")}"
    echo "${GIT_BRANCH,fullName=false}"
    echo "${BUILD_TAG}"
  }
}
}
}
}
