pipeline {
         agent any
         environment {
             server:"103.139.58.136"
         }
         stages {
            stage {'Deploy to server'}{
               steps{
                    sh 'scp -r ${WORKSPACE}/* root@${mukeshnhsrc58136}:/var/www/html/nhsrc_portal'
                   }
              }
        }
   }
                 
