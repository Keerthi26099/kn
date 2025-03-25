pipeline{
  agent any
  stages{
    stage('clone')
    {
      step{
        git "https://github.com/Keerthi26099/kn.git"
      }
    }
    stage('build')
    {
      step{
        sh 'javac H.java'
      }
    }
    stage('run')
    {
      step{
        sh 'java H'
      }
    }
  }
}
