pipeline  {
  agent any
  stages  {
    stage("stage1")  {
      steps  {
         script  {
            bat  "mvn clean install"
            }
          }
        }
     stage("stage2")  {
      steps  {
         echo "On stage 2"
          sleep 5
            }
          }
        }
     }
 }
