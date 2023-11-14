pipeline {
         agent any
         environment{
             staging_server:"103.139.58.136"
         }
         stages {
            stage{'Deploy to remote'}
               steps{
                    sh 'scp -r ${WORKSPACE}/* root@${staging_server}:/var/www/html/'
                   }
              }
        }
   }
                 
