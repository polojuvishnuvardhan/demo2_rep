pipeline
{
agent any 
stages
{
stage('clone')
{
steps{
git "https://github.com/polojuvishnuvardhan/demo2_rep.git"
}
}
stage('bulid')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
