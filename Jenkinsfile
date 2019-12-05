pipeline {
    agent any
    stages {
            stage('Upload to AWS') {
              steps {
                 withAWS(region:'us-west-1',credentials:'AWS ID') {
                   s3Upload(pathStyleAccessEnabled:true, payloadSigningEnable: true,file:'index.html', bucket:'stubcane2019')
                 }
          }
      }  
   }
}

