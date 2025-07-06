pipeline {
  agent any
  stages {
    stage('Pull Code') {
      steps {
        git 'https://github.com/GodwinChukks/Introd-Jenkins.git'
      }
    }
    stage('Build') {
      steps {
        echo 'Build step running...'
      }
    }
  }
}
