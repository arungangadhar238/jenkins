pipeline {
 agent { label 'Demo' }
 stages{
   stage ('testing linux commands') {
     steps{
        sh '''
           ansible --version
           sudo docker build -t .
           '''
     }

   }

 }

}
