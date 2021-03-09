pipeline{
agent any
stages{
stage('branchparameter'){
steps{
  script{
    def value = "origin/value"
    def newvalue = "${value}.replace("origin/","")"
    echo "${newvalue}"  
  }
}
}
}
}
