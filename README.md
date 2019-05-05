# Google Spreadsheet Builder Starter

You can use this project as a reference for interacting with Google Spreadsheet using the Spreadsheet Builder API.

## Setup the Project

##### 1. Clone or download the project sources 

<img src="https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/docs/images/download.png" alt="Download" width="500">

##### 2. (optional) Import the project into IntelliJ IDEA

Click on _Import Project_ and select the folder where have you cloned or downloaded the project files.

<img src="https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/docs/images/import-gradle-0.png" alt="Import to IntelliJ 0" width="500">

Select _Import project from external model_ > _Gradle_

<img src="https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/docs/images/import-gradle-1.png" alt="Import to IntelliJ 0">

Keep the defaults and click _Finish_

<img src="https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/docs/images/import-gradle-2.png" alt="Import to IntelliJ 2">

Whne IntelliJ IDEA is finished with downloading all the necessary libraries you should see the following structure in the _Project_ explorer.

<img src="https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/docs/images/source-tree.png" alt="Source Structure" width="500">


## Setup the Credentials
Visit [Java Quickstart](https://developers.google.com/drive/api/v3/quickstart/java) page and enable the
Drives API for the Quickstart project.


##### 3. Click the _ENABLE THE DRIVE API_ button

![Java Quickstart](docs/images/java-quick-start.png)

##### 4. (optional if not logged in) Log into your Google Account

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/choose-account.png" alt="Choose Account" width="500">

##### 5. Enable the API 

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/enable-api.png" alt="Enable API" width="500">

##### 6. Download credentials JSON file and copy it into `src/main/resources` folder of the project.

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/download-credentials.png" alt="Download Credentials" width="500">

## Run the Application

##### 7. Run the application from the command line using `./gradlew run` or run `App` class from the IDE

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/run-app.png" alt="Run App">

##### 8. Grant permissions page will appear in the browser

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/grant-persmission.png" alt="Grant Permissions" width="300">

##### 9. Confirm granting the permissions

<img src="https://raw.githubusercontent.com/dsl-builders/google-spreadsheet-builder-starter/master/docs/images/confirm-grant.png" alt="Confirm Grant" width="500">

##### 10. Spreadsheet page wil appear in the browser

![Choose Account](docs/images/spreadsheet.png)


## Explore the Code
Now you can explore the code in [App.java](https://github.com/dsl-builders/google-spreadsheet-builder-starter/blob/master/src/main/java/dsl/builders/spreadsheet/google/starter/App.java)

For more information on using Spreadsheet Builder [see the official documentation](http://spreadsheet.dsl.builders/).