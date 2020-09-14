pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        sh 'mvn -U clean package -X -DskipTests'
      }
    }

  }
}