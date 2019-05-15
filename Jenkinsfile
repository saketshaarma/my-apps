pipeline {
    agent any
    stages {
        stage('---Maven Clean---'){
            steps {
                mvn clean install
            }
        }
        stage('---Maven Deploy---'){
          steps {
              mvn deploy
          }
        }
    }
}
