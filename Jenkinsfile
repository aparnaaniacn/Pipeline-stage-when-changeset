pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeset pattern: "*.js"
            }
            steps {
                echo "hello World Changeset JS"
            }
        }
    }
}

