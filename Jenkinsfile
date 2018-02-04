pipeline {
    agent any
    tools {
        maven 'Maven 3.5.2'
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn -v'
                sh 'mvn package'
                sh 'java -cp target/myartifact-0.0.1-SNAPSHOT.jar mygroup.myartifact.App'
            }
        }
    }
}
