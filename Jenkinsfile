pipeline {
    agent any

    stages {
        stage('git clone & build') {
            steps {
                parallel(
                    a: {
                        echo 'git clone'
                    },
                    b: {
                        echo 'build'
                    }
                    )
                }
        }
       
        stage('test') {
            steps {
                echo 'shlomo mhadker'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
