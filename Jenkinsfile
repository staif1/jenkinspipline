pipeline {
    agent any
    stages {
        stage ("CD") {
            steps {
            sh 'cd /home/nikita'
            }
        }
            stage ("pwd") {
                steps {
                sh 'pwd'
            }
        }
        
           stage ("ls -la") {
               steps {
               sh 'ls -la'
            }
        }
        
           stage ("cd ~") {
               steps {
               sh 'cd ~'
            }
        }

           stage ("instal tree") {
               steps {
               sh 'sudo apt-get install tree'
            }
        }
           stage ("instal Java") {
               steps {
               sh 'sudo apt-get install java'
            }
        }
     }
 }


