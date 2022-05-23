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
               sh "docker run -itdp 70:80 httpd"
            }

          }
     }
}

