pipeline {
    agent any

    stages {
        stage("Baixando a imagem"){
            steps {
                git url: 'https://github.com/gilbertolira/Desafio360.git', branch: 'develop'
            } 
        }}
        stage("Buildando"){
            steps {
               script {
                    dockerImage = docker.build("betolira/django-crm:v1")
               
            }
        } }
        stage("deploy"){
            steps {
                echo "realizando o deploy..."
            }        
        }
    }

        