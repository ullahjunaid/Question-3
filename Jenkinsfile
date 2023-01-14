pipeline{
    agent any
    stages{
            stage("Source Code Checkout"){
               steps{
                git branch: 'main', url: 'https://github.com/ullahjunaid/Question-3.git'                }  
            
            }
             stage("Shubam's 2 stage to delete a file"){
               
                steps{
                   powershell 'Remove-Item mylocalfile.txt'
                }
            }
              stage("Shubam's 3rd stage"){
                steps{
                    echo  "This is 3rd stage"
                          
                }
            }
            
         }
}