pipeline{
  agent none
  stages {
    stage('Say Hello') {
      agent{ label 'nodejs-app'}
      steps {
        contanier('nodejs') {
          echo 'Hello World!'   
          sh 'java -version'
        }
      }
    }
  }
}
