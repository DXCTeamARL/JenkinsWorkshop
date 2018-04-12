pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('Maven') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}