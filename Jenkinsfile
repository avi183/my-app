node{
  stage('SCM checkout'){
         git 'https://github.com/avi183/my-app'
  }
  stage('compile-package'){
    def mvnHome = tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
