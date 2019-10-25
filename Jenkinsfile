node{
        stage('SCM Checkout'){
	git 'https://github.com/Valan23aix/maven_war_linux'
	}
	stage('Compile-Package'){
	     def m2_home = tool name: 'maven_3_6_2', type: 'maven'
	     sh "${m2_home}/bin/mvn install"
	}
  }
