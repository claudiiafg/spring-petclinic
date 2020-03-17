pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sh './wmvn clean'
      }
    }

    stage('Test') {
      steps {
        sh 'mvn test'
      }
    }

    stage('Package') {
      steps {
        sh 'mvn package'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo'
      }
    }

  }
}