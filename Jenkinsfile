pipeline {
  agent any
  stages {
    stage('Pull Code') {
      steps {
        git branch: 'main', url: 'https://github.com/GodwinChukks/Introd-Jenkins.git'

      }
    }
    stage('Build') {
      steps {
        echo 'Build step running...'
      }
    }
  }
}
