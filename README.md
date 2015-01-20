###Checkstyle settings for Java code.

  Checkstyle configuration that based on coding conventions from the Java Language Specification at [http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html](http://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html)

  Most Checks are configurable, be sure to consult the documentation at
  [http://checkstyle.sourceforge.net](http://checkstyle.sourceforge.net)

  To completely disable a check, just comment it out or delete it from the file.

  Finally, it is worth reading the documentation.

###Own features:

- Checking for the line length (`LineLength`) increased up to 100 characters
- Configured the check for hidden fields (`HiddenField`) so that it ignores constructor parameters and the parameter of setter methods.
- Disabled the check that a package-info.java file exists for each package (`JavadocPackage`).
- Disabled the check that variables have Javadoc comments (`JavadocVariable`).
- Disabled the check of javadoc formatting (`JavadocStyle`).
- Disabled the check that parameters for methods, constructors, and catch blocks are final (`FinalParameters`).
- Disabled the check that classes are designed for extension (`DesignForExtension`).
- Disabled the check for visibility of class members (`VisibilityModifier`).