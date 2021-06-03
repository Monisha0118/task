pipeline{
  agent any
  stages{
    stage(checkout)
    {
      steps{
        sh "sudo cp index.html /var/www/html"
      }
    }
      stage(build)
      {
        steps{
          echo "Hello"
        }
      }
       stage(test)
      {
        steps{
          echo "devops"
        }
      }
    }
}
