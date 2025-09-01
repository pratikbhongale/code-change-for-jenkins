pipeline{
    agent {label "Dev"}
    stages{
        stage("Hello") {
            steps{
                echo "Hello Checking if pipeline is successfully implemented......."
            }
        }
        stage("Code Cloning.....") {
            steps{
                git url: "https://github.com/pratikbhongale/code-change-for-jenkins.git"
            }
        }
        stage("making dir"){
            steps{
                sh "mkdir jenkins_pipeline"
            }
        }
    }
}