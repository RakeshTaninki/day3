pipeline {
  agent any
  stages {
    stage('aaa') {
      steps {
        git branch: 'main', credentialsId: 'e0002491-fac2-48ee-8196-60684d58603c', url: 'https://github.com/RakeshTaninki/day3.git'
        sh 'ls -la'
      }
    }

  }
}
