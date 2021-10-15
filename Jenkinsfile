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
        
           stage ("instal mc") {
               steps {
               sh 'sudo apt-get install mc -askpass=123qwe123'
            }
        }
     }
 }


