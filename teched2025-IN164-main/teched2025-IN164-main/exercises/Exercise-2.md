# IN164 - Exercise 2 - Create an iFlow for the test message and send the message

## Overview
In this exercise, you will copy an existing iFlow into your own package and configure it to simulate a trading partner.
Replace XX with your participant number wherever it appears.

![IN164_024](assets/IN164_024.png)

Go to Design -> Integrations and APIs.

----

![IN164_025](assets/IN164_025.png)

Create your own package by clicking Create.

----

![IN164_026](assets/IN164_026.png)

Name the package IN164-UserXX (replace XX with your number).

----

![IN164_027](assets/IN164_027.png)

Navigate to the package IN164-SimulatorFlow.

----

![IN164_028](assets/IN164_028.png)

Open the Artifacts tab, click the three dots (...), then click Copy.

----

![IN164_029](assets/IN164_029.png)

In the Copy dialog:
- Rename the iFlow to IN164 - Send EDIFACT Order_UserXX (replace XX with your number).
- Select your package IN164-UserXX (replace XX with your number).
- Click Copy.

----

![IN164_030](assets/IN164_030.png)

To configure the copied iFlow, click Navigate to open the new iFlow.

----

![IN164_031](assets/IN164_031.png)

Open Artifacts, click the three dots (...), then click Configure.

----

![IN164_032](assets/IN164_032.png)

In the Configure screen:
- Set UserId to UserXX (replace XX with your number).
- Click Save, then Deploy.

----

![IN164_033](assets/IN164_033.png)

Confirm the deployment by clicking Yes.
After deployment, the simulated trading partner will send an EDIFACT Order message.

----
Continue with: [Exercise 3 - monitor the message](Exercise-3.md)

Please give us feedback for this session **IN164**

![QR Code](assets/survey_QR.png)
