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
                echo sh'https://github.com/yalbornoz/Tsoft/blob/cc35988f857448f6e26b6670e0d23f8d11d2e9bf/Hola%20Mundo.md'
            }
        }
        stage('Escribir') {
            steps {
                writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."
            }
        }
    }
}
