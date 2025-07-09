pipeline {
    agent {
        label 'headche-label'
    }
    stages{
        stage('Build') {
            steps {
                echo "Build pipeline from feature branch"
            }
        }
         stage('scans') {
            steps {
                echo "scans pipeline from feature branch"
            }
        }
         stage('dockerbuild') {
            steps {
                echo "docker pipeline from feature branch"
            }
        }
         stage('deployment') {
            steps {
                echo "deploying pipeline from feature branch"
            }
        }
    }
}
