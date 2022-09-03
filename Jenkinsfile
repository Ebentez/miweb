pipeline {
  agent any
  stages {
    stage('paso1') {
      steps {
        script {
          pipeline {
            agent any

            stages {
              stage('Hello') {
                steps {
                  echo 'Hello World'
                }
              }
            }
          }
        }

      }
    }

  }
}