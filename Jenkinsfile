pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn -version'
        bat 'mvn clean install'
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
