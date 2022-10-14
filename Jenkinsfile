pipeline{
    agent any

    stages{
        stage ('trigger'){            
            steps{            
            sh 'curl -k -X POST http://35.90.231.19:8080/job/jenkins-master/build --user <username>:<api-token>'
            }
        }
    }
}
