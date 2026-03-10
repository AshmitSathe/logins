node{
    stage('DEV')
    stage('QA')
{  input 'QA DEPLOY'}
    stage('deploy TO PROD')
    { bat 'xcopy index.html C:\\apache-tomcat-11.0.18-windows-x64\\apache-tomcat-11.0.18\\webapps\\ROOT /E /I /Y'  }}
