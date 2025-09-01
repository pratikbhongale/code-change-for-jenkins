pipeline{
    agent {label "Dev"}
    stages{
        stage("Hello") {
            steps{
                echo "Hello Checking if pipeline git is successfully triggered......."
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
