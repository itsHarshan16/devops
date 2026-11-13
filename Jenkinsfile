
pipeline {
    agent any

    stages {
        stage('Python Diagnostic') {
            steps {
                bat 'echo Checking Jenkins user'
                bat 'whoami'

                bat 'echo Checking Python location'
                bat 'dir "C:\\Users\\STUDENT\\AppData\\Local\\Programs\\Python\\Python313\\python.exe"'

                bat 'echo Checking Python version'
                bat '"C:\\Users\\STUDENT\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" --version'
            }
        }
    }
}
