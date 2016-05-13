#Maven + Jasmine + Angular TDD BoilerPlate

A simple Maven project which demonstrates integration between the Maven-Jasmine-Plugin and a basic Angular project for Test Driven Development.
The reason I wrote this guide is because I wanted to bootstrap a Maven+Javascript TDD workflow which had minimal external dependencies, specifically no NodeJS dependency. 

### Notable
  * Jasmine uses a .html file as a `TestRunner`
  * The Maven Jasmine plugin comes with it's own default .html template. Override the `customRunnerTemplate` configuration setting in your `pom.xml` to define a custom Template which will allow you to import your project-specific JavaScript dependencies. 
  * The reference for which variables are accessible from the .html template can be found here : [Spec Runner Template Reference](http://searls.github.io/jasmine-maven-plugin/spec-runner-templates.html)
  * The Maven-Jasmine-Plugin comes with a handy [Reference for Jasmine Config Variables](https://searls.github.io/jasmine-maven-plugin/test-mojo.html)

### References

  * Thanks to [@fellippenardi](https://github.com/felippenardi) for his boilerplate on [AngularJS + Jasmine](https://github.com/felippenardi/angularjs-and-jasmine-test-boilerplate)
  * (The Jasmine Maven Plugin)[http://searls.github.io/jasmine-maven-plugin/index.html]
  * (Angular JS)[https://angularjs.org/]
