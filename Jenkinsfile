pipeline {
    agent any
    stages {
        stage('Build Application') {
            steps {
                'clean install package'
            }
            post {
                success {
                    echo "Now Archiving the Artifacts...."
                    archiveArtifacts artifacts: '**/*.war'
                }
            }
        }
        stage('Deploy in Staging Environment'){
            steps{
                 echo 'Building sample maven project'
 
            }
            
        }
        stage('Deploy to Production'){
            steps{
                 echo "builing sample maven project"
            }
        }
    }
}

