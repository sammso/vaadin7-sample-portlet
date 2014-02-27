## Sample Vaadin 7 Portlet.

## Compile and deploy:

Change the bundle root from pom.xml to point root folder of your Liferay 6.2 bundle. 

The location has been marked, with following comment:

```
<!-- POINT THIS TO YOUR BUNDLE ROOT -->
```

and run

```
mvn package
mvn liferay:deploy
```

