pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building.. and Deploying....'
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\MSBuild.exe HelloWorld.sln /t:ReBuild /p:Configuration=Release /p:OutDir=C:\Users\andre\Desktop\Servidor
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
    }
}