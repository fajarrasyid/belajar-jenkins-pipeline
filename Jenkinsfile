pipeline {
    agent {
        node{
            label "linux && java11"
          }
      }
    stages{
        stage("Build"){
            steps{
               echo("hellow build 1")
               sleep(10)
               echo("hellow build 2")
               echo("hellow build 3")
            }
        }
     stage("Test"){
            steps{
                echo("hellow test 1")
                sleep(10)
                echo("hellow test 2")
                echo("hellow test 3")
            }
        }
     stage("Deploy"){
            steps{
                 echo("hellow deploy 1")
                 sleep(10)
                 echo("hellow deploy 2")
                 echo("hellow deploy 3")
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
