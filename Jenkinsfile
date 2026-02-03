pipeline {
    agent {
        node {
            label "linux && java11"
        }
    }
    stages {

        stage("Build") {
            steps {
                echo("helo Build 1")
                echo("helo Build 2")
                echo("helo Build 3")
            }
        }

        stage("Test") {
            steps {
                echo("helo Test")
            }
        }

        stage("Deploy") {
            steps {
                echo("helo Deploy")
            }
        }
    }

    post {
        always {
            echo "saya berusaha untuk mengerti dan paham"
        }
        success {
            echo "yap, akhirnya saya sukses"
        }
        failure {
            echo "saya gagal, tapi akan mencoba terus"
        }
        cleanup {
            echo "ayo kita bangkit"
        }
    }
}