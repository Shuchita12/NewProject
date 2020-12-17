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
                export PATH=$PATH:/usr/local/bin 
                 sh "npm install"
            }
        
        

    }
    }
}