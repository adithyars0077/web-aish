pipeline
{
agent any
stages
{
stage('clean')
{
steps
{
sh 'rm -r *'
sh 'rm -r ../../../../www/html/*'
}
}
stage('git clone ')
{
steps
{
sh 'git clone https://github.com/adithyars0077/web-aish.git -b aish'
}
}
stage ('deploy')
{
steps
{
sh 'mv web-aish/* ../../../../www/html'
}
}
}
}
