pipeline {
         agent any
         environment {
             server_name:"mukeshnhsrc58136"
             mukeshnhsrc58136:"103.139.58.136"
         }
         stages {
            stage {'Deploy to server'}{
               steps{
                    sh 'scp -r ${WORKSPACE}/* root@${mukeshnhsrc58136}:/var/www/html/'
                   }
              }
        }
   }
                 
