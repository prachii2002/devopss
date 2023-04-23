pipeline {
    agent any
    stages{
        stage('checking python version') {
            steps {
                bat 'python -V'
            }
        }

        stage('REPO Cloning'){
            steps {
                bat 'xcopy /S "*" "D:/XAMPP/htdocs/devops" /Y'   
//[add path of folder that you created in htdocs]
            }
        }

        stage('Print done'){
            steps{
                echo 'Done!'
            }
        }
    }
}
