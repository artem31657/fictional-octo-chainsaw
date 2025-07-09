pipeline {
  stages{
    stage('Checkout') {
      steps {     
		    echo 'step Git Checkout'
		    // Извлечение из системы контроля версий в рабочий каталог на сервере TestNode 
		    checkout scm
	    }
    }
    stage('Build') {
		  echo $(cat README.md)
	  }
  }
}
