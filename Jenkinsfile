pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                changeset pattern: "*WORLD.js", caseSensitive: true
            }
            steps {
                echo "hello World Changeset JS"
            }
        }
    }
}

