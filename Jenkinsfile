pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        echo "Pulling code from Github"
        checkout scm
      }
    }

    stage ('Build') {
      steps {
        echo "Running build step.."
      }
    }
  }

  post {
    success {
      echo "Pipeline completed successfully!!!!!!"
    }
  }
}
