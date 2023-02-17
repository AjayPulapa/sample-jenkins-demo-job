// pipeline{
// agent any
// stages{
//  stage("Build")
//  {
//    echo "Build"
// }
// stage("Deploy")
//  {
//    echo "Deploy"
// }
// }

pipeline{
agent any
stages 
{
stage('Build') 
{
steps{
  echo "node {
     stage("Build")
  {
     echo "Build Success"
  }
  "
}
}
stage('Test') 
{
steps{
echo "Testing the Project.........."
}
}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
}
}
}
}
