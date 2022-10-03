pipeline {
    agent any
    triggers {
  pollSCM('* * * * *')
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello '
                sleep 5
            }
        }
          stage('build') {
            steps {
                echo 'build'
                sleep 5
            }
        }
          stage('test') {
            steps {
                echo 'test'
                sleep 5
            }
        }
          stage('deploy') {
            steps {
                echo 'deploy'
                sleep 4
            }
        }
        stage('aut') {
            steps {
                echo 'aut'
                sleep 5
            }
        }
        stage('package') {
            steps {
                echo 'package'
                sleep 5
            }
        }
    }
}
