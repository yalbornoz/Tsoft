pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Hello') {
            steps {
                readFile file: "Hola Mundo.txt"
               
            }
        }
        stage('Escribir') {
            steps {
                writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
            }
        }
    }
}
