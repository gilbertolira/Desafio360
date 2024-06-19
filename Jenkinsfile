pipeline {
    agent any

    stages {
        
        stage("deploy"){
            steps {
                echo "realizando o deploy..."
            }        
        }
        
        stage("Baixando a imagem"){
            steps {
                git url: 'https://github.com/gilbertolira/Desafio360.git', branch: 'develop'
            } 
        }
       
        
    }
}    

        