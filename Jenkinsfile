pipeline{
  agent any
  stages{
    stage(checkout)
    {
      steps{
        sh """
              javac simple.java
              javac simple
           """
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
