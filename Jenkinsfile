pipeline {
    agent any

tools{nodejs "node"}

    environment{
        CI = 'true'
    }
     
    stages{
        stage('Build') {
            steps {
                echo 'Shuchita'
                export PATH=/usr/local/bin:$PATH
                 sh "npm install"
            }
        
        

    }
    }
}