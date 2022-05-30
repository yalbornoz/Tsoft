pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Hola Mundo') {
            steps {
                echo 'Hola Juan Manuel!'
            }
        }
        stage('Escribir') {
            steps {
                writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
            }
        }
    }
}
