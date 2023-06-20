pipeline{
    agent any
    
    environment{
        probar="hola desde la variable"
    }

    stages{

        stage ("primer stage"){
            steps{
                sh "python3 practica.py"
            }
        }

        stage ("variable"){
            steps{
                echo "${probar}"
            }
        }
    }
}