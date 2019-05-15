pipeline {
    agent any
    tools {
      maven 'Maven 3.6.1'
    }
    stages {
        stage('---Maven Clean---'){
            steps {
              sh 'mv clean install'
            }
        }
        stage('---Maven Deploy---'){
          steps {
            sh 'mv clean deploy'
          }
        }
    }
}
