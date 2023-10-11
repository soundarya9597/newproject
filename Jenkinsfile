pipeline{
agent any
stages{
stage("maven build"){
steps{
echo "this is jenkinsfile"
}
}
  stage("dev deploy"){
    when{
      branch"develop"
    }
steps{
echo "deploying to dev"
}
}
  stage("test deploy"){
    when{
      branch"test"
    }
    steps{
echo "deploying to test"
}
  }
  stage("prod deploy"){
when{
  branch"prod"
}
    steps{
echo "deploying to main"
}
  }
}
}
