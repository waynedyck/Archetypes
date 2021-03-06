#MGWT Basic Archetype

Basic MGWT archetype which uses only one layout for both phone, tablet and desktop. It has an “About” activity and one
other sample activity wired up to illustrate basic functionality. All layout is done with UiBinder rather than through code.

Good starting point if you are new to MGWT.

##Maven Archetype Usage

1. Clone the repo and then`cd Archetypes/generated/mgwt-basic` and type `mvn install`
2. Goto the directory where you want to create your project.
3. Rename the parameter `-DgroupId=com.example.mgwt.app` to a package naming scheme that works for you.
4. Rename the parameter `-DartifactId=mgwt-basic-example` to a project title you like.
5. Rename the parameter `-Dmodule=App` to a name that starts with a capital. Name it like `MyApp` or `MyProject`.
6. Run the mvn archetype generator below.

```
mvn archetype:generate \
-DarchetypeCatalog=local \
-DarchetypeGroupId=gov.wa.wsdot.data.archetypes \
-DarchetypeArtifactId=mgwt-basic-archetype \
-DarchetypeVersion=1.0-SNAPSHOT \
-DgroupId=com.example.mgwt.app \
-DartifactId=mgwt-basic-example \
-Dmodule=App
```
