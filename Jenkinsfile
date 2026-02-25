node('dotnet') {
    stage('Build') { 
        sh 'dotnet restore' 
        sh 'dotnet build --no-restore' 
    }
}
