pipeline {
    agent any
    stages {
        stage("Build Master") {
            when {
               branch 'master'

            }
            steps {
                echo "Building on master"
            }
        }
        stage("Build Dev") {
            when {
               branch 'dev'

            }
            steps {
                echo "Building on dev"
            }
        }
        stage("Build classs") {
            when {
               branch 'class'

            }
            steps {
                echo "Building on class"
            }
        }
    }
}
