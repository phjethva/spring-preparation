# MVN Commands

----------

### Commands:

- #### How to check if newer versions are available for the relevant dependencies used in your project?
  `mvn versions:display-dependency-updates`

- #### How to check if newer versions are available for the relevant plugins used in your project?
  `mvn versions:display-plugin-updates`

- #### Updating the Dependencies in the project

    - ##### Manually update the versions in pom.xml.
    - ##### Use Maven command to update the dependencies automatically:
      `mvn versions: use-latest-versions`
    - ##### To update Dependency versions that are updated in the properties block:
      `mvn versions:update-properties`

----------