pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Ingreso una accion para hacer deploy'
               
            }
        stage('Escribir') {
            steps {
                writeFile file: "output/usefulfile.txt", text: "This file is useful, archive it."
            }
        }
    }
}
