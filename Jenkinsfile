@Libraray('my-shared-library') _
pipeline{
    agent any

    stages{

        stage('Git Checkout'){

            steps{
            gitCheckout(
                branch:"main",
                url: "https://github.com/AbhayGRT/Jenkins_shared_lib.git"
            )
                
            }

        }
        stage('Unit Test Maven'){

            steps{
                script{
                    mvnTest()
                }

                
            }

        }

    }
}
