node('master')
{
stage('git checkout')
{
git 'https://github.com/jyotheesh/mortgage-new-BC.git'
}
stage(java build')
{
sh 'mvn clean install sonar:sonar -Dsonar.password=admin -Dsonar.login=admin'
}
  
}
