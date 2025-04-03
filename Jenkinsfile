pipeline {
  agent { label 'agent1'}
  
  stages {
    stage('Mensaje') {
      steps {
        echo 'Mensaje prueba'
      }
    }
    stage('Saludo') {
      steps {
        sh 'echo "hola"'
      }
    }
  }
}
