pipeline {
  agent any
  stages {
    stage('Checkout Source') {
      steps {
        echo 'Suren test Checkout Source From Git'
      }
    }
    stage('Build') {
      steps {
        echo 'Suren test Build'
      }
    }
    stage('Build image') {
      steps {
        echo 'Suren test Build Image'
      }
    }
    stage('Push Image') {
      steps {
        echo 'Suren test Push Image to Harbour'
      }
    }
    stage('Pull Image') {
      steps {
        echo 'Suren test Pull Image From Harbour'
      }
    }
    stage('Deploy App') {
      steps {
        echo 'Suren test Deploy App'
      }
    }
    stage('Test App V3') {
      steps {
        echo 'Deployed App to test'
      }
    }
    stage('Release') {
      steps {
        echo 'Suren test Release App V2'
      }
    }
  }
}