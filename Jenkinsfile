pipeline{
    agent any

    environment{
        probar="hola desde la variable"
    }

    stages{

        stage ("primer stage"){
            steps{
                sh "echo hola"
            }
        }

        stage ("variable"){
            steps{
                echo "${probar}"
            }
        }
    }
}