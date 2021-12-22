pipeline {
    agent any
    stages {
        stage('Git from Jenkinsfile') {
            steps {
                echo 'Get source from from Jenkinsfile'
                //git 'https://github.com/keyvankeyhan/cicd-test'
            }
        }
        stage('Build from Jenkinsfile') {
            steps {
                echo 'Build Application from Jenkinsfile'
            }
        }
        stage('Test from Jenkinsfile') {
            steps {
                echo 'Run script test.sh from Jenkinsfile'
                //sh './test.sh'
            }
        }
    }
}
