pipeline {
    agent any
    stages{
        stage('checking'){
            steps {
                git branch: 'master', url: 'https://github.com/ADirin/lectdemo_en.git'

            }
        }

        stage('build'){
            steps{
                bat 'mvn clean install'
            }
        }

    }
}
