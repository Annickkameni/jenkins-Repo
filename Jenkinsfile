pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo " I am etech engineur"
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}
