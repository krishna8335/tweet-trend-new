pipeline {
    agent{
        node{
            label'maven'
        }
    }
    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/krishna8335/tweet-trend-new.git'
            }
        }
    }
}
