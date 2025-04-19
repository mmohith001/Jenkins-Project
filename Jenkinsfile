pipeline{
    agent{
                docker { image 'mmohith001/python-img:v1' }
            }
    stages{
        stage('clone') {
            steps {
                git url: 'https://github.com/mmohith001/Jenkins-Project.git'
            }
        }
        stage('Build') {
            
            steps {
                echo 'Building....'
                sh 'python3 --version'
            }
        }
    }
}