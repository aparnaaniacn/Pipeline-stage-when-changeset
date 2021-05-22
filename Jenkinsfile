pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeset pattern: "*.js", casesensitive: true
            }
            steps {
                echo "hello World Changeset JS"
            }
        }
    }
}

