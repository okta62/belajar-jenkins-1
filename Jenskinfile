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
                powershell '<PATH_KE_PHP_EXE> index.php'
            }
        }

    }
}
