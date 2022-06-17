pipeline { 
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'hello'
                echo 'hello world'
            }
        }
     stage('Run Scripts') { 
            steps { 
                sh 'python script.py'
            }
        }

   
    }
}