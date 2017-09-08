pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    cd /Users/xxzeng/Documents/mysrc/fun/draw-n-guess
                    pwd
                    git pull
                    ls -lah
                '''
            }
        }
    }
}