node {   
   stage('Build') {
        bat '''
        javac -cp "C:\\Users\\Emma\\junit4\\junit-4.13-beta-1.jar";"C:\\Users\\Emma\\hamcrestcore\\hamcrest-core-2.1.jar";. "Student.java" "studentTest.java"
        '''
   }
  
   stage('Test') {
        bat '''
        java -cp "C:\\Users\\Emma\\junit4\\junit-4.13-beta-1.jar";"C:\\Users\\Emma\\hamcrestcore\\hamcrest-core-2.1.jar";. org.junit.runner.JUnitCore "studentTest"
        '''
   }
}
