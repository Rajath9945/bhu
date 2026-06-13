pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/Rajath9945/Bhu.git'
                sh 'mvn clean package'
                sh 'java -jar target/*.jar'
            }
        }
    }
}
