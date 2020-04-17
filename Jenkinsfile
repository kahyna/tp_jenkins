pipeline {
        agent {
                docker {
                        image 'nodejs:latest'
                        
                }
        
        }
        #environment {
         #       CI = 'true'
        #}
        stages {
                stage('Build') {
                        steps {
                                sh 'npm install'
                        }
                }
                #stage('Test') {
                 #       steps {
                  #              sh './scripts/test.sh'
                   #     }
                #}
        }
}
