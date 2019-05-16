pipeline {
    agent any
    stages {
        stage('---Maven Clean---'){
            steps {
              withMaven(maven: 'maven-3')
              sh 'mvn clean install'
            }
        }
        stage('---Maven Deploy---'){
          steps {
            withMaven(maven: 'maven-3')
            sh 'mvn clean deploy'
          }
        }
    }
}
