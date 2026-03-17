pipeline {
    agent any 

    stages {

        stage('clone'){
            steps {
                git url: 'https://github.com/Akshay-nadig/jenkins_demo_1.git',
                    branch: 'main'
            }
        }

        stage('Run Script') {
            steps {
                sh 'python3 script.py'
            }
        }
    }
}
