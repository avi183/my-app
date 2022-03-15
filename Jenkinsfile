@Library("app-lib") _
pipeline {
  agent any

  oy to Tomcat') {
      steps {
        tomcatDeploy(["172.31.13.38","172.31.13.38","172.31.13.38"],"ec2-user","tomcat-dev")
      }
    }
  }
  post {
    success {
      archiveArtifacts artifacts: 'target/*.war'
      cleanWs()
    }
  }
}
