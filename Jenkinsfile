node("s1") 
	{
	stage("scm")
		{
			git "https://github.com/Lohithreddy-k/jenkins_practice.git"
		}
	stage("run")
		{
			sh "java demo.java"
			sh "python3 main.py"
		}
	}
