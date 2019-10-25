node{
        stage('SCM Checkout'){
	git 'https://github.com/Valan23aix/maven_war_linux.git'
        }
	stage('Compile-Package'){
	     def m2_home = tool name: 'maven_3_6_2', type: 'maven'
	     sh "$M2_HOME/bin/mvn package"
	    }
    }
