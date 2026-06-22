pipeline {
    agent any

    stages {
        stage('Checkout Info') {
            steps {
                echo 'Code checked out from GitHub successfully!'
                sh 'pwd && ls -la'
            }
        }
        stage('Simulate Build') {
            steps {
                echo 'Pretending to build something...'
                sh 'echo "Build step ran at: $(date)"'
            }
        }
        stage('Simulate Test') {
            steps {
                echo 'Pretending to run tests...'
                sh 'echo "All tests passed (simulated)"'
            }
        }
        stage('New Stage From Git') {
            steps {
                echo 'This stage was added purely by editing GitHub - no Jenkins UI changes!'
            }
        }
    }
}
