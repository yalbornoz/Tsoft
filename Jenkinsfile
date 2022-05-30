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
                echo 'Hola Mundo!'
            }
        }
        stage('Escribir') {
            steps {
                writeFile file: "output/dummy.txt", text: "This file is useful, need to archive it."
            }
        }
    }
}
