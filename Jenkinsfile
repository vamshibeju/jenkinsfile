pipeline{
agent any
stages{
stage('branchparameter'){
steps{
  script{
    def branch= "${GIT_BRANCH}"
    echo "${branch}"
  }
}
}
}
}
