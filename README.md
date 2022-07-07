# cucumber_Second_Project_
My dependencies
Selenium-java version 3
Web driver manager
Cucumber-java
Cucumber- junit
HTMLunitDriver for headless testing 

My folder structure
under java package  I have
Pages
Steps
Utilities
Runners

In the feature file I write my scenario I use Grekhin language Given , When ,Then annotations and write my step definitions.

  it reads the tag given and navigates to features
   2. It finds all the scenarios which have that given tag and start executing one by one
   3. When a scenario found with given tag, it immediately finds the step implementation for it
   with glue
   4. After executing all, it creates given reports with plugin
   Later, we integrate our Runner class with Maven  in the pom.xml using surefire plugin. And
   this helps us to run different Tags(suites) with Maven commands, later to be integrated with
   Jenkins and pipelines.