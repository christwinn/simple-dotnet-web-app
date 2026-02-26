pipeline {
    agent {label "dotnet"}
    stages {
        stage('Restore .NET') {
            steps {
                sh 'dotnet restore' 
            }
        }
        stage('Build') {
            steps {
                sh 'dotnet build --no-restore' 
            }
        }
    }
}
        
//node('dotnet') {
//    stage('Build') { 
//        sh 'dotnet restore' 
//        sh 'dotnet build --no-restore' 
//    }
//}
