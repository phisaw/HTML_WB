pipeline {
  agent {
    label 'node'
  }
  stages {
    stage('A') {
      post {
        always {
          echo '========always========'
        }

        success {
          echo '========A executed successfully========'
        }

        failure {
          echo '========A execution failed========'
        }

      }
      steps {
        echo '========executing A========'
      }
    }

  }
  post {
    always {
      echo '========always========'
    }

    success {
      echo '========pipeline executed successfully ========'
    }

    failure {
      echo '========pipeline execution failed========'
    }

  }
}