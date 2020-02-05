pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            echo 'building'
          }
        }

        stage('build1') {
          steps {
            echo 'cross check'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'devlopment'
      }
    }

    stage('implement') {
      steps {
        echo 'showing'
      }
    }

    stage('end') {
      parallel {
        stage('end') {
          steps {
            echo 'finish'
          }
        }

        stage('end1') {
          steps {
            echo 'over'
          }
        }

      }
    }

  }
}