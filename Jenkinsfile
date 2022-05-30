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
              String content = new File("Hola Mundo,md").text 
                echo 'new File'
                }
            }
        }
        stage('Escribir') {
            steps {
                writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
            }
        }
    }
