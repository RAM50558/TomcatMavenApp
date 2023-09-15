pipeline {
    agent { node{ label 'slave1'}}
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean install -f pom.xml'

            }
        }
    }
}
