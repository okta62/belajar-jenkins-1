pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/okta62/belajar-jenkins-1.git', branch: 'main'
            }
        }

        stage('Run PHP') {
            steps {
                powershell '"C:\\xampp2\\php\\php.exe index.php"'
            }
        }

    }
}
