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

    
  }

  // No triggers block – keeps it manual
}
