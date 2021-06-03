pipeline{
  agent any
  stages{
    stage(checkout)
    {
      steps{
        sh "sudo cp index.html /var/lib/jenkins/workspace/My_First_Job_main"
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
