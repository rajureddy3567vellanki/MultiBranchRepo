pipeline
{

   agent any
{

   stages
{
   stage('checkout git repo')
{
   steps
{
     sh 'git url: https://github.com/rajureddy3567vellanki/MultiBranchRepo.git'
}
 stage('validate the project')
 {

   steps
{

   sh 'mvn install'
}
}
}
}
}
 



  
