pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sleep 30
            echo 'Bees Buz'
          }
        }

        stage('Unbuild') {
          steps {
            echo 'Slickery 1'
            sleep(time: 1, unit: 'MINUTES')
            echo 'Slickery 2'
          }
        }

      }
    }

  }
}