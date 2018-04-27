pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean package'
        echo 'echo " First Build Message"'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing will be done here'
      }
    }
    stage('Deploye') {
      steps {
        echo 'deployment will be done here'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_161'
    MAVEN_HOME = 'C:\\Program Files\\apache-maven-3.5.3'
  }
}