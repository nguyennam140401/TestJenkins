pipeline {
  agent any
  stages {
    stage('Clone') {
      parallel {
        stage('Clone') {
          steps {
            git 'https://github.com/nguyennam140401/TestJenkins.git'
          }
        }

        stage('abcde') {
          steps {
            sh 'node -v'
          }
        }

      }
    }

  }
}