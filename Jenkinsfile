pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                sh 'echo "this is build stage"' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo "this is test stage"' 
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "this is deploy stage 2"'
            }
        }
    }
}
