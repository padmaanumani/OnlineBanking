pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'mvn --version'
                bat '${MAVEN_HOME} mvn clean package'
            }
        }
    }
}
