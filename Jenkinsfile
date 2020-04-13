pipeline{
    agent any
    stages{
        stage ("build")
        {
         steps
         {
             echo " build a project."
         }
        }
        stage ("test")
        {
          steps
          {
              echo "testing the project"
          }
        }
        stage ("clean up")
        {
          steps
          {
              echo "cleaninig up workspace"
               cleanWs()
          }
        }
    }
}
