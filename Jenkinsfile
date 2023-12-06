pipeline {   
    agent any

    stages {  
        stage('sprint1 branch new udated' ) { 
            steps { 
               sh 'echo "This is sprint branch new updated"' 
            }
        }
     
        stage('test') { 
            steps {              
	       sh 'echo "test application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
