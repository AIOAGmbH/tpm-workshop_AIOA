# IN164 - Exercise 7 — Working with the Functional Acknowledgment

Overview

![IN164-7_01](assets/IN164-7_01.png)
In the left-hand navigation, go to *Design* > *B2B Scenarios*.

----
----

![IN164-7_02](assets/IN164-7_02.png)
Open *Agreements* in *B2B Scenarios*.

----
----

![IN164-7_03](assets/IN164-7_03.png)
Open the *Trading Partner Agreement* between your partners (for example, IN164-UserXX and your counterpart).
Use your participant number (XX) where applicable.

----
----

![IN164-7_04](assets/IN164-7_04.png)
Within your *Trading Partner Agreement*, navigate to the *B2B Scenario* section.

----
----

![IN164-7_05](assets/IN164-7_05.png)
Switch the *Trading Partner Agreement* to *Edit* mode to modify the *Functional Acknowledgment* settings.

----
----

![IN164-7_06](assets/IN164-7_06.png)
Select *Interchange (outgoing)* and check the *Receiver Functional Acknowledgment* checkbox.

----
----

![IN164-7_07](assets/IN164-7_07.png)
Go to the *Communication* tab and set *Channel* to the endpoint through which your trading partner will send the CONTRL message.

----
----

![IN164-7_08](assets/IN164-7_08.png)
The channel is already prepared. Select *Company.AS2.Sender*.

----
----

![IN164-7_09](assets/IN164-7_09.png)
Click *Save* to store the changes to the *Trading Partner Agreement*.

----
----

![IN164-7_10](assets/IN164-7_10.png)
Click *Update* so the changes are written to the *Partner Directory*.

Then send a test message (by deploying the *Integration Flow (iFlow)* in the *Package* you copied). After that, open the *B2B Monitor* to view the status of the *Functional Acknowledgment*.

----
----

![IN164-7_11](assets/IN164-7_11.png)
Because the CONTRL message your trading partner sends back is a partial acknowledgment, you can adjust the setting that controls how this partial status is displayed in monitoring. Change the setting and send another message to see the different behavior.

Congratulations — you have finished the TechEd exercise!

Please give us feedback for this session **IN164**

![QR Code](assets/survey_QR.png)
