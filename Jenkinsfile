pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build app'
            }
        }
        stage('test') {
            steps {
                echo 'test app'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy app'
            }
        }
    }
    post 
    {
        always
        {
            emailext body: 'summaey', subject: 'pipeline satatus', to: 'sreekanthpv12@gmail.com'
        }
    }
}
