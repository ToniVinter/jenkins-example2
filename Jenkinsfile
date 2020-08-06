pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn -version'
        sh 'mvn clean install'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying..'
      }
    }

  }
}
