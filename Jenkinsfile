pipeline{
    agent any

    stages{
        stage('Child Build'){
            steps{
                echo 'Child Pipeline: Build Started...'
            }
        }

        stage('Child Test'){
            steps{
                echo 'Child Pipeline: Testing Started...'
            }
        }

        stage('Child Deploy'){
            steps{
                echo ' Child Pipeline: Deployment Completed...'
            }
        }
    }
}