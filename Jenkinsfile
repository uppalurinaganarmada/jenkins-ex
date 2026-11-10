pipeline{
  agent any
    stages{
      stage("Build")
      {
      steps{
	echo "This is build phase"
	}
      }
      stage("Test"){
      steps{
	echo "This is test phase"
	}
      }
      stage("Deploy"){
      steps{
	echo "This is deploy phase"
	}
     }
   }
post{
  success{
    echo "Successfully created a pipeline"
}
failure{
echo "Failed"
}
}
}
