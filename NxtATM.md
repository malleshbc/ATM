**NxtATM:**

This solution addresses major physical card transaction issues like Frauds(Skimming, Shimming), Lost/Stolen Card, Damage Card, Forgot to carry card/ATM PIN. The major advantage of this solution is the ATM withdrawal can be done without touching ATM keypad or screen. This is much helpful during this pandemic situation and the people who are much worried about the germs. Also this solution gives the other value added services like Search nearby ATM locations and verify the facilities in place like Number of ATM machines, Parking available, Deposit machine availability, Money availability for withdrawal and particular denomination currency availability

**Installation:**

These features can be easily integrated with existing mobile banking app., as part of banking app upgrade the feature can be incorporated.

**Problems solved:**

\* No need to carry card

\* No need of touch key pad or screen on ATM.

\* It works only just with the Net banking app.

\* Easy, faster and secured withdrawal.

\* Ease of finding ATM machines with available money, denomination and other facilities.

**How it works:**

**I. Withdrawal Scenario:**

1. User reaches the ATM locations.

2. Login into phone banking via Bank provided mobile app.

3. Chooses the NxtATM option to withdraw amount.

4. S/m asks for ATMID you are present and authenticate info and send request( Device Id or EMI

number registered hiddenly sent).

5. The ATMID mentioned in the request screen switches to QR code display for scanning and

authenticating.

6. User scans the QR code the mobile bank app will validate with the response vs request for

device ID or EMI number.

7. It prompts for the amount to enter for withdrawal once the authenticated.

8. Based on the Balance and other funds availability validations the NxtATM will dispense Cash.

![](RackMultipart20200604-4-1dyhfxn_html_202c1f7e39495219.png)

**II. Finding nearest ATM and it&#39;s facilities.**

1. User logs into mobile banking.

2. Chooses the NxtATM Menu and select nearby ATM.

3. Mobile bank app will display all the below facilities in the mouse over ATM

a. Number of ATM machines in the selected location.

b. Whether parking available in the selected ATM location.

c. Deposit machine available in the location.

d. Security personnel available in the location.

d. Request amount wish to withdraw from the ATM

e. Request denomination of currency.

**Technology Used:**

Java, J2EE, Spring Boot, JSP, Android, HTML5, Google Map API and Rest API.

**Limitations:**

\* Current design works with Same organizational ATM

\* Depends on Mobile Data services.

**Scope of enhancement**

\* Solution can be used for all other operations performed in ATM.

\* Other bank ATM&#39;s can be added to the chain of this solution by utilizing NPCI server.

\* The solution of available facility details can be enhanced to

other public services