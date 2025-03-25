pipeline
{
 agent any
stages{
stage('clone')
{
steps{
 git "https://github.com/Keerthi26099/kn.git"
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
