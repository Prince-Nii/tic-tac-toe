pipeline { 
    
    agent any

    stages{
        stage("build") {

            steps{
                echo 'Building the application....'
                nodejs('Node-21.4.0') {
                    sh 'yarn install'
                }
            }
        }

        stage("test"){

            steps{
                echo 'Testing the application....'
            }
        }

        stage("deploy"){

            steps{
                echo 'Deploying the application....'
            }
        }
    }
}
