pipeline {
    agent {
        node{
            label "linux && java11"
          }
      }
    stages{
        stage("Build"){
            steps{
                echo("hellow build")
            }
        }
     stage("Test"){
            steps{
                echo("hellow test")
            }
        }
     stage("Deploy"){
            steps{
                echo("hellow deploy")
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
