pipeline {
  agent any

  tools {
    maven "3.9.9"
  }

  stages {
    stage('Build') {
      steps {
        bat 'mvn -B -q package'
      }
    }
  }

}
