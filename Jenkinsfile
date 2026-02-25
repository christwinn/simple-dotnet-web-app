pipeline {
    agent agentX
    stages {
        stage('Build') { 
            steps {
                sh 'dotnet restore' 
                sh 'dotnet build --no-restore' 
            }
        }
    }
}
