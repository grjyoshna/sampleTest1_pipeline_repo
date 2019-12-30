node{
  stage('SCM Checkout')
  {
    git 'https://github.com/grjyoshna/sampleTest1'
  }
  stage('Compile-Package')
  {
    //Get maven home path
    def mvnHome=tool name: 'M3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
