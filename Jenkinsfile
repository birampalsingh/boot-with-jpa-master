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
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_161'
    MAVEN_HOME = 'C:\\Program Files\\apache-maven-3.5.3'
  }
}