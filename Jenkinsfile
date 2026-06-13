pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "mvn -DskipTests clean package"
            }
        }
        stage('Test') {
            steps {
                // This is where you run your shell script inside a pipeline!
                sh "mvn test"
            }
        }
        
    }
}
