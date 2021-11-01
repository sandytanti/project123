node('master')                                                                         
{
       stage('ContinuousDownload_MASTEr')                                            
      {
           git 'https://github.com/intelliqittrainings/maven.git'         
      } 
      stage('ContinuousBuild_MASTER')                                                    
     {
          sh 'mvn package'                                                                 
     }
} 
