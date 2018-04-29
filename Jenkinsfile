pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean package'
      }
    }
    stage('Test') {
      steps {
        echo 'Here Testing is Done'
      }
    }
    stage('Deploye') {
      steps {
        echo 'Deployment will be Done Here'
      }
    }
  }
}