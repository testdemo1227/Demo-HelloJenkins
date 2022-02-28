node{
  stage('SCM Checkout') {
    git 'https://github.com/testdemo1227/Demo-HelloJenkins'
  }
  stage('Package-compiling') {
    sh 'mvn package'
  }
}
