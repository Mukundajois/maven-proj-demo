pipeline {
  agent any

  tools {
    maven 'Maven 3'  
    jdk 'JDK 17'     
  }

  stages {
    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }
  }

  // No triggers block – keeps it manual
}
