pipeline{

agent{label "maven-agent"}
  stages{
    stage("prep"){
      echo "hello world"
      git "git@github.com:This-is-my-first-github/Remote-repo1.git"
      sh "mvn comment deployed"
      }
    stage("build"){
      echo "building application"
    }
    stage("deploy"){
      echo "building application"
    }
  }
}
