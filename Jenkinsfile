pipeline {
    agent {
        node{
            label "linux && java11"
          }
      }
    stages{
        stage("helo"){
            steps{
                echo("hellow")
            }
        }
    }
    post {
        always{
            echo "hello"
          }
        success{
            echo "sukses"
          }
        failure{
            echo "gagal"
          }
        cleanup{
            echo "kelar"
          }
      }
}
