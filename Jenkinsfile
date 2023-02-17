// node
// {
//     stage("build")
//     {
//         echo "Build Success"
//     }
//     stage("test")
//     {
//         echo "tested Success"
//     }
//     stage("Deploy")
//     {
//         echo "Deploy Success"
//     }
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
