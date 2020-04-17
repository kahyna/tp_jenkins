pipeline {
        agent {
                docker {
                        image 'nodejs:latest'
                        
                }
        
        }
        
        stages {
                stage('Build') {
                        steps {
                                sh 'npm install'
                        }
                }
                
        }
}
