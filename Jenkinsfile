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
     echo "Build the Project"
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
