pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Buzz Buzz') {
          steps {
            echo 'Bees Buzz!'
          }
        }

        stage('Sting Sting') {
          steps {
            echo 'Wasps Sting!'
          }
        }

      }
    }

    stage('Bees Bees') {
      steps {
        echo 'Buzz, Bees, Buzz!'
      }
    }

  }
}