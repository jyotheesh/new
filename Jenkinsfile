node('master')
{
stage('git checkout')
{
git 'https://github.com/jyotheesh/new'
}
stage('java build')
{
sh 'mvn clean install sonar:sonar '
}
}
