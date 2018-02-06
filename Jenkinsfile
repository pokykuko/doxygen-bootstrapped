pipeline {
  agent {
    node {
      label 'SlaveCentos_002'
    }
    
  }
  stages {
    stage('WsUpdate') {
      steps {
        git(url: 'https://github.com/LukasSchopp/jenkins.git', branch: 'develop', changelog: true)
      }
    }
  }
}