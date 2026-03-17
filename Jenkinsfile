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
                python 'chmod +x script.py'
                python './script.py'
            }
        }
    }
}
