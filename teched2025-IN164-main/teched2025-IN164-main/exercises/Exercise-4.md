# IN164 - Exercise 4 - Onboard the Trading Partner by Copying

Overview
If you create an agreement with the Bind option, you cannot modify the process or change the MIGs and MAGs. Because our trading partner needs slightly different MIG and MAG that you will create in the following exercises, we first need an agreement that allows you to modify the MIGs and MAGs. You can do this by instantiating the agreement from the template using the Copy option.

As usual: replace XX with your participant number wherever it appears.

![IN164_038](assets/IN164_038.png)
Go to Design -> B2B Scenarios.

----

![IN164_039](assets/IN164_039.png)
Go to Agreements and open your agreement (IN164-UserXX-bind).

----

![IN164_040](assets/IN164_040.png)
Because you want to create a new agreement for the same trading partner, first deactivate the bound one. Click Deactivate.

----

![IN164_041](assets/IN164_041.png)
Confirm by clicking OK.

----

![IN164_042](assets/IN164_042.png)
Click Create to create a new agreement.

----

![IN164_043](assets/IN164_043.png)
Select the same template as before: IN164-SimpleExerciseTemplate.

----

![IN164_044](assets/IN164_044.png)
Choose Copy from Template, select your trading partner (IN164-UserXX), then click Open Draft.

----

![IN164_045](assets/IN164_045.png)
Name the agreement IN164-UserXX-copy, then click Save and Activate.

----

![IN164_046](assets/IN164_046.png)
Confirm activation by clicking OK.

----

![IN164_047](assets/IN164_047.png)
Before making changes, verify that the new agreement works. Go to Design -> Integrations and APIs.

----

![IN164_048](assets/IN164_048.png)
Open your package IN164-UserXX (replace XX with your number).

----

![IN164_049](assets/IN164_049.png)
Go to Artifacts, click the three dots (...) on the iFlow, then click Deploy. This simulates the trading partner and sends an EDIFACT Order.

----

![IN164_050](assets/IN164_050.png)
Go back to Monitor -> B2B Scenarios.

----

![IN164_051](assets/IN164_051.png)
Click the Interchanges tile.

----

![IN164_052](assets/IN164_052.png)
Click Go and check whether you can find the interchanges for your trading partner. You should see two lines: one for the incoming Order and one for the outgoing Order Response.

----
Continue with: [Exercise 5 - Create a New Message Implementation Guideline](Exercise-5.md)

Please give us feedback for this session **IN164**

![QR Code](assets/survey_QR.png)
