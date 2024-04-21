pipeline {   
    agent any

    stages {   
        stage('Master branch') { 
            steps { 
               sh 'echo "This is master branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "This is sprint1 branch..."'
            }
        }

        stage("sprint2") { 
             steps { 
                sh 'echo "This is sprint2 latest branch..."'
            }
        }  
    }
}
