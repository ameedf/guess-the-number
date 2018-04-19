## guess-the-number
#an assignment for practicing EJB 3.x, JPA, HTML + AJAX
<ol>
  <li>The 'guess-the-number.docx' file contains the assignment.</li>
  <li>The 'hw-teams.xlsx' file includes the teams.</li>
  <li>The following link has a full Wildfly server with configurations: https://transfernow.net/412sz9o62oa0</li>
</ol>

Next, you'll see the basic persistence.xml file. You should add your classes to the file.

persistence.xml:
<persistence xmlns="http://xmlns.jcp.org/xml/ns/persistence"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://xmlns.jcp.org/xml/ns/persistence
             http://xmlns.jcp.org/xml/ns/persistence/persistence_2_1.xsd"
	version="2.1">

	<persistence-unit name="my-pu" transaction-type="JTA">
		<jta-data-source>java:/datasources/project</jta-data-source>
		<class>p1.p2......MyClass1</class>
		<class>p1.p2......MyClass2</class>
	</persistence-unit>
</persistence>
