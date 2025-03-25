pipeline
{
 agent any
stages{
stage('clone')
{
steps{
 git ""
}
}
stage('build')
{

 steps{
sh 'javac Hello.java'
}
}
stage('run')
{
 steps{
sh 'java Hello'
}
}
}
}
