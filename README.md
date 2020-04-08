# facebook2RDF

The project is for connecting the Facebook API to get informations of the user and saving in an ontology with RDF format, you can also query the ontology by SPARQL.


=================== Step to run =====================

- Install the necessary dependences with Gradle, make sure that you have installed Gradle 
- Right click the project and choose "Gradle - Refresh Gradle project"
- Replace your id of Facebook and your token in the filed "FacebookApi.java" (lien 45, 46) (you have to have a developer account for the Facebook API https://developers.facebook.com/tools/explorer/)
- Replace the route where you want to output the ontology in the field "JsonToRDF.java" (lien 123)
- Run the project
- You can modify the SPARQL request in the field "SparqlTest.java" (lien 23)
- Re-run the project to verify the result
