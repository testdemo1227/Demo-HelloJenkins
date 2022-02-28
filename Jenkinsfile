node{
  stage('SCM Checkout') {
    git 'https://github.com/testdemo1227/Demo-HelloJenkins'
  }
  stage('Package-compiling') {
    def homemvn = tool name: 'Maven', type: 'maven'
    sh '${homemvn}/bin/mvn package'
  }
}
