pipeline{
agent any
stages{
stage("maven build"){
steps{
echo "this is jenkinsfile"
}
}
  stage("dev deploy"){
steps{
echo "deploying to dev"
}
}
  stage("test deploy"){
steps{
echo "deploying to test"
}
  }
  stage("prod deploy"){
steps{
echo "deploying to main"
}
  }
}
}
