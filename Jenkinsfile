pipeline {
    agent none
    stages {
        node('dotnet')
        stage('Build') { 
            steps {
                sh 'dotnet restore' 
                sh 'dotnet build --no-restore' 
            }
        }
    }
}
