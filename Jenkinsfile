pipeline {
         agent any
    stage "build"
     steps {
               echo 'Hola, estoy construyendo'
                 }
    
  stage "build output"
    writeFile file: "output/usefulfile.txt", text: "This file is useful, need to archive it."

   
}
