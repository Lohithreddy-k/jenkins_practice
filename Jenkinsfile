node 
	{
	stage("scm")
		{
			git "https://github.com/Lohithreddy-k/jenkins_practice.git"
		}
	stage("run")
		{
			sh "java demo.java"
			sh "python main.py"
		}
	}
