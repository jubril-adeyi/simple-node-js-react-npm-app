pipeline {
    agent {
      label 'agent1'
    }
   tools {
      nodejs 'nodejs'
    }
   stages {
    stage('Build') {
      steps {
        sh 'npm version'
        sh 'npm install'
      }
    
    }
   
   }

}
