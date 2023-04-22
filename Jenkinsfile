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
        sh "apk add nodejs"
        sh 'npm version'
      }
    
    }
   
   }

}
