pipeline {
  agent any

  stages {
    
    stage('Clone') {
      steps {
        git url:'https://github.com/gopikagopal2517/jenkins-simple-demo/new/main',
        branch: 'main'
      }
    }

    stage('Run  Script') {
      steps {
        sh 'chmd +x script.sh'
        sh './script.sh'
      }
    }
  }
}
