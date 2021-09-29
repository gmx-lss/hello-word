pipeline{
    agent any
    options { skipStagesAfterUnstable() }
    stages  {
        stage(合并分支){
            steps{
                dir("$merge"){
                    sh ''' 
                        echo "yes"
                    '''                  
                }
            }
        }
    }
}
