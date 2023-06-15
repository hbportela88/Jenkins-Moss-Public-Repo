pipeline {
    agent any 

      environment{

        AAA_TOP_LEVEL_VAR = 'TopLevel'
      }
          stages {

              stage ("build") {
                  steps {

                           sh 'echo $AAA_TOP_LEVEL_VAR'      							
                      }                    							
                  }                        
          }
}			
