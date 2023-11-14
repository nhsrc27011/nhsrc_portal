pipeline {
         agent any
         environment {
             stagin_server:"103.139.58.136"
         }
         stages {
            stage{'Deploy to remote'}{
               steps{
                    sh 'scp -r ${WORKSPACE}/* root@${mukeshnhsrc58136}:/var/www/html/'
                   }
              }
        }
   }
                 
