
pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                script {
                    def startTime = System.currentTimeMillis()

                    echo 'Building the application...'

                    def endTime = System.currentTimeMillis()
                    echo "Build execution time: ${(endTime - startTime) / 1000.0} seconds"
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    def startTime = System.currentTimeMillis()

                    echo 'Testing the application...'

                    def endTime = System.currentTimeMillis()
                    echo "Test execution time: ${(endTime - startTime) / 1000.0} seconds"
                }
            }
        }

        stage('Deploy') {
            steps {
                script {
                    def startTime = System.currentTimeMillis()

                    echo 'Deploying the application...'

                    def endTime = System.currentTimeMillis()
                    echo "Deploy execution time: ${(endTime - startTime) / 1000.0} seconds"
                }
            }
        }
    }
}

