pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Checkout') {
            steps {
              git branch: 'main', url: 'pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Checkout') {
            steps {
              git branch: 'main', url: 'https://github.com/adilfettach/JenkinsCraftOrdre'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean '
            }
        }

        stage('Test') {
            steps {
                bat 'mvn  test'
            }
        }

    }

    post {
        success {
            echo 'Build succeeded!'

        }

        failure {
             echo 'Build failed!'
        }
    }
}'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean '
            }
        }

        stage('Test') {
            steps {
                bat 'mvn  test'
            }
        }

    }

    post {
        success {
            echo 'Build succeeded!'

        }

        failure {
             echo 'Build failed!'
        }
    }
}
