pipeline
{
   agent 
{
 node
{
   label 'built-in'
   customWorkspace "/mnt/project"
}
}
  stages
     {
	stage ('httpd container')
          {
	    steps
	    {
	       sh "docker run -itdp 90:80 httpd"
	    }
        
	  }
     }
}
