pipeline {
    agent any
    stages {
      stage('Build') {
        steps {
          sh 'echo \'Hello DevOps\''
          sh '"
                  echo "Multiline shell steps works too"
                  ls -lah
               "'
        }
      }
    }
  }
