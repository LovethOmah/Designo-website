Pipelline{
    agent any
    stages{
        stages(Greet user){
            steps{
                echo "Hello Loveth
                i hope you are understandinf the class"
        }
    }
        stage(Build image){
            steps{
            sh '''
                sudo docker build -t testimage:1
                echo "Building image please wait loading -------> completed"
                '''
        
        }
    }
        stage("check docker image"){
            steps{
                sh 'sudo docker images'
            }
        }
    
    }
}