pipeline {
    agent any

    stages {
        stage("Baixando a imagem"){
            steps {
                git 'https://github.com/gilbertolira/Desafio360.git'
            } 
        }
        stage("Buildando"){
            steps {
               script {
                    dockerImage = docker.build teste
                }
               
            }
        }
        stage("deploy"){
            steps {
                echo "realizando o deploy..."
            }        
        }
    }
}
        