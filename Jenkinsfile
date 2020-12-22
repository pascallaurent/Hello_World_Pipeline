pipeline {
  agent any 
  stages {
    stage(‘Build’) {
      steps {
        sh 'echo "ello World"'
        sh '"
                  echo "Multiline shell steps works too"
                  ls -lah
               "'
      }
    }
  }
}
