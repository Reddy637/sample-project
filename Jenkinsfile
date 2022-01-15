node
{
   checkout scm
 
   stage ('Validate')
   { 
      bat 'mvn validate'    
   }
   stage ('Package')
   {
   bat 'mvn clean install'
   }
   stage ('site')
   {
   bat 'mvn site'
   }
   
}  
 







