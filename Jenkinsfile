pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'this is my ${myvar}'
        sh 'echo "Message printed by shell script ${myvar}"'
      }
    }

  }
  environment {
    myvar = '100'
    weight = '200'
  }
}