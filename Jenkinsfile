
 pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Hello World"'
               echo "Multiline shell steps works build id  ${env.BUILD_ID} Build Name ${env.BUILD_DISPLAY_NAME} node name ${env.NODE_NAME} job name ${env.JOB_NAME}"
             
            }
        }
    stage('Deploy') {
            steps {
                sh 'echo "Test Deploy"'
        
            }
        }
            }
}
