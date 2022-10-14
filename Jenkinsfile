pipeline {
     agent any
  tools {
    maven "mvn3"
  }
  
  stages {
    stage('pullscm') {
      steps {
        git branch: 'main', credentialsId: 'Github', url: 'git@github.com:Avinasharma799/functional-testing.git'
      }
    }
    stage('execute test') {
      steps {
        sh "mvn clean test"
      }
    }
  }
}
white_check_mark
eyes
raised_hands






