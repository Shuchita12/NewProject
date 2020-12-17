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
                sh "export PATH=$PATH:/usr/local/bin 
                    npm install"
            }
        
        

    }
    }
}