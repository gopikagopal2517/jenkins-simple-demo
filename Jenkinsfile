pipeline {
  agent any

  stages {
    
    stage('Clone') {
      steps {
        git url:'https://github.com/gopikagopal2517/jenkins-simple-demo.git',
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
