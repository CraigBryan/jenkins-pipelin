pipeline {
    agent any 

    stages {
        stage('echo') { 
            steps {
                powershell 'ls' 
                powershell 'echo.ps1'
            }
        }
    }
}