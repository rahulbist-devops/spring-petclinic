pipeline 
{
agent any
      stages{      
stage('Build'){
steps {
sh '''cd spring-petclinic
      ./mvnw package
      java -jar target/*.jar
'''
}
}
}

}
