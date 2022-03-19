pipeline {
    agent {
      docker {
        image 'node:9-alpine'
      }
    }
    stages {
        stage('Node') {
          steps {
              script {                
                sh 'node --version'
              }
          }
      }
    }
}
