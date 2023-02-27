pipeline {   
     agent any 
     tools {nodejs "nodejs"}
            stages {
                stage('build') {
                    steps {
                         
                          sh 'npm install'
                            sh 'forever start index.js'
                            sh 'echo "hi"'
                          

                        }
                     }
                }
}
