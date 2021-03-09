pipeline{
agent any
stages{
stage('branchparameter'){
steps{
  script{
    def branch= "{GIT_BRANCH.replace("origin/","")}"
    echo "${BRANCH}"
    
    echo "${BUILD_TAG}"
  }
}
}
}
}
