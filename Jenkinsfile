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
                bat 'xcopy /S "*" "C:/xampp/htdocs/newxampp" /Y'   
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
