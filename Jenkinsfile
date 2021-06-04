pipeline{
  agent any
  stages{
    stage(checkout)
    {
      steps{
        sh "index.html"
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
