# TestAutomation.MWL.UI

Here some notes about setting up the test automation project

## Selenium Server (Grid)
Download it from the Selenium website
https://selenium-release.storage.googleapis.com/3.141/selenium-server-standalone-3.141.59.jar

### Execute the Hub and Node
This command is for the Hub which downloaded to the C: drive
- C:\java -jar selenium-server-standalone-3.141.59.jar -role hub

Then run this command to execute the Node
- C:\java -jar selenium-server-standalone-3.141.59.jar -role node –hub

## Visual Studio Solution
Once downloaded perform a Build operation to ensure all the NuGet packages are installed correctly.
