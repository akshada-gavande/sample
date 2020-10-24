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
                input('Do you want to proceed?')
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