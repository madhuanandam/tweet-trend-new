pipeline{
    agent any

    stages{
        stage('clone'){
            steps{
                git branch: 'main', url: 'https://github.com/madhuanandam/tweet-trend-new.git'
            }
        }
        stage('build'){
            stapes{
                sh 'mvn clean build'
            }
        }
    }
}