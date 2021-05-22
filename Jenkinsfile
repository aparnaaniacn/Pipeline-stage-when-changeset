pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeset glob: "*.js"
            }
            steps {
                echo "hello World Changeset JS"
            }
        }
    }
}

