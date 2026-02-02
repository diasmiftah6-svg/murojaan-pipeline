pipeline {
    agent {
        node {
            label "linux && java11"
        }
    }
    stages {
        stage("helo") {
            steps {
                echo("helo pipeline")
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