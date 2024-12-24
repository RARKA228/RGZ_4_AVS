pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Compiling main.cpp'
                sh 'g++ -o main main.cpp'
            }
        }
        stage('Run') {
            steps {
                echo 'Running compiled program'
                sh './main'
            }
        }
    }
}
