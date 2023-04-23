pipeline {
    agent any
    stages {
        stage('Checkout and Clone') {
            steps {
                git branch: 'master', url: 'https://github.com/prachii2002/devopss.git'
            }
        }
        stage('Build') {
            steps {
                bat 'echo "Building the code"'
            }
        }
        stage('Deploy') {
            steps {
                bat 'copy *.html D:\\xampp\\htdocs\\devops\\a.html'
            }
        }
    }
}
