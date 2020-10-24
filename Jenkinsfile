pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is akshada from edubridge'
            
                }
        }
        stage('Two'){
            
            steps {
                echo "hi dear "
            }
        }
        stage('three') {
                steps {
                        echo 'Hi, this is Akshada from edureka'
            
                }
        }
        stage('Four') {
                parallel {
                    stage('Unit Test') {
                            steps{
                                    echo "Running the unit test..."
                                }
                        }
                        
                               
                        }  
        }
    }
}