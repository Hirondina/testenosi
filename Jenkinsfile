pipeline {
  agent {
    docker {
      image 'maven:3.3.9-jdk-7'
    }
    
  }
  stages {
    stage('Inicialize') {
      steps {
        sh '''echo PATH = ${PATH}
echo M2_HOME = ${M2_HOME}
mvn clean '''
      }
    }
  }
}