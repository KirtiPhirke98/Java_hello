node {

        
    stage ("checkout")  {
       checkout([$class: 'GitSCM', branches: [[name: 'main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/KirtiPhirke98/Java_hello.git']]])
            sh javac Hello_Java
    }

       
   

      }

