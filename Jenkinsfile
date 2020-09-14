pipeline {
  agent any
  stages {
    stage('start') {
      steps {
        sh '''when branch \'master\'
mvn -U clean package -X -DskipTests'''
      }
    }

  }
}