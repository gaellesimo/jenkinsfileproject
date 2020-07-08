pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo "Hi, this is Gaelle from Cameroon"
                        echo "We are starying the testing"
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area"
                  }
            }
      }
}
