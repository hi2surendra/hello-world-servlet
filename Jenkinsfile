
 pipeline {
    agent any
      tools {
            maven 'maven3'
    }
 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Mavern version"'
              sh 'mvn -version'
                sh 'which mvn'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Hello test"'
               echo "Multiline shell steps works build id  ${env.BUILD_ID} Build Name ${env.BUILD_DISPLAY_NAME} node name ${env.NODE_NAME} job name ${env.JOB_NAME}"
             
            }
        }
    stage('Deploy') {
            steps {
                sh 'echo "Test Deploy Hello World"'
        
            }
        }
            }
}
