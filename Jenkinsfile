pipeline{
agent any
stages{
stage("dev deploy"){
  when{
    branch "develop"
  }
steps{
echo "deployinh to dev"
}
}
  stage("test deploy"){
  when{
    branch "test"
  }
}
  stage("prod deploy"){
  when{
    branch "main"
  }
}
}
}
