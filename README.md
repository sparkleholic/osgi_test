    
    javac -classpath org.eclipse.osgi_3.10.2.v20150203-1939.jar HelloActivator.java
    jar -cfm HelloWorld.jar HelloWorld.mf HelloActivator.class
    java -jar org.eclipse.osgi_3.10.2.v20150203-1939.jar -console
    osgi> ss
    osgi> install file:HelloWorld.jar
    osgi> ss
    osgi> start 5
    osgi> stop 5`

