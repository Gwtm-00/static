pipeline {
     agent any
     stages {
         stage('Build') {
             steps {
                 sh 'echo "Pipeline Working"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                 '''
             }
         }
     }
}