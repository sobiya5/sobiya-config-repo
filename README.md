mvn -B org.apache.maven.plugins:maven-archetype-plugin:3.3.1:generate -D archetypeGroupId=com.adobe.aem -D archetypeArtifactId=aem-project-archetype -D archetypeVersion=54 -D appTitle="My Site" -D appId="mysite" -D groupId="com.mysite"
--------------------------------------------------
mvn clean
mvn -PautoInstallSinglePackage clean install
