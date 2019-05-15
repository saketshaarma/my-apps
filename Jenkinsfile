pipeline {
    agent any
    stages {
        stage('---Maven Clean---'){
            steps {
                def mvnHome = tool name: 'maven-3', type: 'maven'
                ${mvnHome/bin/mvn} clean install
            }
        }
        stage('---Maven Deploy---'){
          steps {
              def mvnHome = tool name: 'maven-3', type: 'maven'
                ${mvnHome/bin/mvn} deploy
          }
        }
    }
}
