pipeline{
agent any
stages{
stage('branchparameter'){
steps{
  script{
    def value = "vamshi/value"
    def newvalue = "${value}.replace("vamshi/","")"
    echo "${newvalue}"  
  }
}
}
}
}
