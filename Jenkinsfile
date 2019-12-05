pipeline {
    agent any
    stages {
            stage('Upload to AWS') {
              steps {
                 withAWS(region:'us-west-1',credentials:'AWS') {
                   s3Upload(pathStyleAccessEnabled:true, payloadSigningEnabled: true,file:'index.html', bucket:'stubcane2019')
                 }
          }
      }  
   }
}

