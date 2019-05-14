pipeline 
{
	agent { label 'javanode' }
	stages
	{
		stage('checkout')
		{
			steps
			{
				git 'https://github.com/jaya-g/practice.git'
			}
		}
		stage('Build')
		{
			steps
			{
				echo 'Build'
			}
		}
	}
}
