pipeline {
    agent any
    tools {
        maven 'Maven 3.5.2'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn -v'
            }
        }
    }
}
