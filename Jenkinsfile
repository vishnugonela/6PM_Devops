pipeline (){
    agent any
    stages{
        stage('first_stage'){
            steps{
                sh "echo Hello"
            }
        }

        stage('second_stage'){
            steps{
                sh '''
                   echo Hello World
                   echo This is pipeline job
                   date
                '''
            }
        }

    }
    
}
