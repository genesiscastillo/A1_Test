mvn archetype:generate -DgroupId=cesar.castillo -DartifactId=gittool -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

bundle:install mvn:http://localhost:8082/artifactory/my-maven-virtual-repo!kcc/metadata-kcc/1.0/metadata-kcc-1.0.jar

my-maven-virtual-repo!kcc/metadata-kcc/1.0/metadata-kcc-1.0.jar



6.023.126-5

aa11


 javax.mail:mailapi:jar:1.4.3
 
 mvn install:install-file -Dfile=mailapi-1.4.4.jar -DgroupId=javax.mail -DartifactId=mailapi -Dversion=1.4.3 -Dpackaging=jar
 
 cl.contraloria.siapertra.repo:contentManager-siaper:jar:2.2.1
 
 mvn install:install-file -Dfile=contentManager-siaper-2.2.1.jar -DgroupId=cl.contraloria.siapertra.repo -DartifactId=contentManager-siaper -Dversion=2.2.1 -Dpackaging=jar
 
 javax.inject:javax.inject:jar:1.0.0.redhat-5
 
 javax.inject-1.0.0.redhat-5.jar
 mvn install:install-file -Dfile=javax.inject-1.0.0.redhat-5.jar -DgroupId=javax.inject -DartifactId=javax.inject -Dversion=1.0.0.redhat-5 -Dpackaging=jar
 ----
 
 org.jboss.spec.javax.ejb:jboss-ejb-api_3.1_spec:jar:1.0.2.Final-redhat-3
 jboss-ejb-api_3.1_spec-1.0.2.Final.jar
 
 mvn install:install-file -Dfile=jboss-ejb-api_3.1_spec-1.0.2.Final.jar -DgroupId=org.jboss.spec.javax.ejb -DartifactId=jboss-ejb-api_3.1_spec -Dversion=1.0.2.Final-redhat-3 -Dpackaging=jar
 
 ----------
 
 org.jboss.logmanager:jboss-logmanager:jar:1.5.4.Final-redhat-1
 
 jboss-logmanager-1.5.4.Final.jar
 
 mvn install:install-file -Dfile=jboss-logmanager-1.5.4.Final.jar -DgroupId=org.jboss.logmanager -DartifactId=jboss-logmanager -Dversion=1.5.4.Final-redhat-1 -Dpackaging=jar
 ---------
 
 xalan:xalan:jar:2.7.1.redhat-11
 
 xalan-2.7.1.redhat-11.jar
 mvn install:install-file -Dfile=xalan-2.7.1.redhat-11.jar -DgroupId=xalan -DartifactId=xalan -Dversion=2.7.1.redhat-11 -Dpackaging=jar
 -------------------------
 org.jboss.spec.javax.el:jboss-el-api_2.2_spec:jar:1.0.4.Final-redhat-1
 
 jboss-el-api_2.2_spec-1.0.4.Final-redhat-1.jar
 
 mvn install:install-file -Dfile=jboss-el-api_2.2_spec-1.0.4.Final-redhat-1.jar -DgroupId=org.jboss.spec.javax.el -DartifactId=jboss-el-api_2.2_spec -Dversion=1.0.4.Final-redhat-1 -Dpackaging=jar
 
 ------------
 
  org.jboss.spec.javax.servlet:jboss-servlet-api_3.0_spec:jar:1.0.2.Final-redhat-2, 
  
  jboss-servlet-api_3.0_spec-1.0.2.Final-redhat-2.jar
  
  mvn install:install-file -Dfile=jboss-servlet-api_3.0_spec-1.0.2.Final-redhat-2.jar -DgroupId=org.jboss.spec.javax.servlet -DartifactId=jboss-servlet-api_3.0_spec -Dversion=1.0.2.Final-redhat-2 -Dpackaging=jar
  -------------------------------------------------
  org.jboss.spec.javax.faces:jboss-jsf-api_2.1_spec:jar:2.1.28.Final-redhat-1, 
  jboss-jsf-api_2.1_spec-2.1.28.Final-redhat-1.jar
  mvn install:install-file -Dfile=jboss-jsf-api_2.1_spec-2.1.28.Final-redhat-1.jar -DgroupId=org.jboss.spec.javax.faces -DartifactId=jboss-jsf-api_2.1_spec -Dversion=2.1.28.Final-redhat-1 -Dpackaging=jar
  ----------------------
  
  javax.jms:jms:jar:1.1: 
  
  javax.jms-1.1.jar
  
  mvn install:install-file -Dfile=javax.jms-1.1.jar -DgroupId=javax.jms -DartifactId=jms -Dversion=1.1 -Dpackaging=jar