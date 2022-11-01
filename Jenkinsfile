pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                echo 'cloningggggg ...'
                sh 'rm -fr web'
                sh 'git clone https://github.com/jabbourdan/web.git'
            }
        }
    }
}
