pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                     echo 'Hola, estoy construyendo'
                 }
                 }
         }

         stages {
                  stage('Escriibir') {
                           steps {         
                         new File('Program.Files.Jenkins.tsfot.txt').withWriter('UTF-8') 
                         { writer
                   try {
                            writer << 'hello world\n'
                            } finally {
                             writer.close()
                       }
                  }                     }
}
