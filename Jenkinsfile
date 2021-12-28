pipeline {
  agent any
  stages {
    stage('first_stage') {
      parallel {
        stage('first_stage') {
          steps {
            sh 'echo Hello'
          }
        }

        stage('Parallel_stage01') {
          steps {
            sh 'echo "Parallel 01"'
          }
        }

      }
    }

    stage('second_stage') {
      steps {
        sh '''
                   echo Hello World
                   echo This is pipeline job
                   date
                '''
      }
    }

  }
}