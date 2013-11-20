archetype-webapps-java-angularjs
================================

webapps-java-angularjs archetype for creating web application with AngularJS 1.2.x with ngResource , Hibernate 4.x, Spring Core 3.x, Jersey 1.x, DBUnit.


###Required 

* Maven installed 

###Features & Benefits 

* DAO Generic implemented; 
* Service Generic implemented; 
* Structure for DBUnit done; 
* Spring 3.x and Hibernate 4.x configured; 
* MySql 5.x 
* Jersey 1.x Configured; 

###How to Install local?

**Step 1**

```java
git clone git@github.com:camilolopes/archetype-webapps-java-angularjs.git
```

**Step 2**

* Go to the folder and execute: 

```java
mvn clean install 
```

**Step 3**

* create new maven project via Eclipse ;
* in Catalog choose **All Catalogs**;
* in filter type: br.

Now its is expected you see in group id: *br.com.its.archetypes.angularjs.java*

* choose the archetype and go ahead clicking in next 

Done your project was created with Java + angularJS

###How to custom? What should I change? 

Update thease files according to your configuration for project, such as: data base connection, packages names etc. There are comments where you should inform data. 

* app-context.xml 

* test-context.xml


###Conclusion 

webapps-module-java-angularjs was created to avoid and help to create JEE project using angularjs with basic structure with basic frameworks. Of course we can update, remove any framework that you do not need for you project. Feel free and send pull request. 
