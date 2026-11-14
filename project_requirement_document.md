# Enerlytics – Intelligent Electricity Billing, Consumer Dispute Resolution & Consumption Analytics System

## 1. What Our Project Aims to Achieve

We have selected **Enerlytics** as our Database Systems project. The main idea of this project is to develop a system that makes electricity billing easier for consumers and helps electricity-provider staff manage billing-related information.

Through this system, we want consumers to be able to check their electricity bills, view their electricity consumption, compare their current usage with previous months, check payment records, and submit complaints if they find any problem with a bill or meter reading.

We also want to provide staff with a way to review consumer information, manage billing records, and handle complaints. Our aim is to make the billing process more organized and transparent for both consumers and staff.

## 2. What Problems Our Project Will Solve

Consumers sometimes face different problems related to electricity billing. For example, they may receive a bill that is much higher than expected, find a meter reading that they believe is incorrect, or have difficulty checking whether their payment has been recorded.

They may also find it difficult to submit a complaint and know what happens after submitting it. On the staff side, managing consumer records, bills, payments, and complaints separately can make the work confusing and time-consuming.

Our project aims to help with these problems:

- Consumers can check their bills without depending on paper bills.
- Consumers can compare electricity consumption from different months.
- Unusual increases in electricity usage can be highlighted so consumers can investigate them.
- Consumers can submit complaints about incorrect bills, meter readings, or payment records.
- Consumers can check the status of their complaints.
- Staff can review consumer billing information and handle complaints in an organized way.
- Consumers can view their payment records and identify unpaid bills.

Enerlytics will help organize this information in one system. It cannot guarantee that every billing problem will be automatically detected or solved.

## 3. What the System Will Do and How It Will Behave

**Consumer Accounts and Dashboard**

Enerlytics will provide separate accounts for consumers and staff. Consumers will be able to access their own electricity information, while staff will have access to the features needed for their work. A consumer dashboard will show the latest bill, due date, payment status, electricity consumption, and complaint updates.

**Bill Details and Payment Information**

Consumers will be able to view their current and previous electricity bills. Bills will show details such as the billing period, meter readings, units consumed, charges, total amount, and due date. The system will also display recorded payment information and show whether a bill is paid, unpaid, overdue, or disputed.

**Electricity Consumption Analysis**

The system will provide simple consumption charts and summaries so consumers can compare their monthly electricity usage and notice increases or decreases. It will also show recorded meter readings. Missing readings or unusual changes in consumption may be highlighted for staff to review, but these warnings will not automatically mean that a bill or reading is incorrect.

**Consumer Complaints and Tracking**

Consumers will be able to submit complaints about bills, meter readings, or payment records by selecting the relevant bill and describing the problem. Each complaint will receive a reference number and a status, such as Submitted, Under Review, More Information Required, Resolved, Rejected, or Closed. Consumers will be able to check the progress and read the response.

**Staff Review and Management**

Authorized staff will be able to review consumer records, bills, meter readings, payments, and complaints. They can investigate complaints, record decisions, and approve billing corrections when needed. The system may also show staff summaries of unpaid bills, overdue bills, and complaints waiting for review. It will use the information available and will not automatically decide that fraud has occurred or change a bill just because a complaint is submitted.

## 4. What Scenarios and Situations the System Will Handle

We want Enerlytics to handle the following practical situations:

### Scenario 1: A Consumer Checks a Bill

A consumer logs in and opens the latest electricity bill. The system displays the billing month, meter readings, units consumed, charges, total amount, and due date.

**Expected behaviour:** The consumer can understand the bill and check whether it has been paid.

### Scenario 2: A Consumer Receives an Unexpectedly High Bill

A consumer notices that the latest bill is much higher than the previous month's bill. They open the consumption section and compare their monthly usage.

**Expected behaviour:** The system shows the change in consumption and helps the consumer decide whether to submit a complaint. It does not automatically declare the bill incorrect.

### Scenario 3: A Consumer Complains About a Meter Reading

A consumer believes that the meter reading on their bill is incorrect. They select the relevant bill, describe the problem, and submit a complaint.

**Expected behaviour:** The system records the complaint, provides a reference number, and allows the consumer to track its status.

### Scenario 4: A Bill Is Corrected

After investigating a complaint, staff find that a correction is necessary. An authorized staff member updates the relevant billing information and records the reason.

**Expected behaviour:** The system shows the corrected information and keeps a record of the complaint and its outcome.

### Scenario 5: An Unusual Meter Reading Is Entered

A staff member enters a meter reading that is lower than the previous reading or results in a very large change in consumption.

**Expected behaviour:** The system highlights the reading for staff to review. It does not automatically accuse anyone of fraud or assume that the reading is correct.

### Scenario 6: Staff Check Overdue Bills

A staff member wants to see which bills have passed their due dates and are still unpaid.

**Expected behaviour:** The system displays the relevant overdue bills to authorized staff.

### Scenario 7: A Consumer Tries to Open Another Consumer's Bill

A consumer attempts to access a bill or complaint that belongs to another account.

**Expected behaviour:** The system denies access and keeps the other consumer's information private.

### Scenario 8: A Complaint Is Rejected

Staff investigate a complaint but find that the available billing information does not support the requested correction.

**Expected behaviour:** Staff record the reason for rejection, and the consumer can view the decision and its explanation.

## 5. What Is Included and Excluded from Our Project Scope

### Included in Our Project

We plan to include these features in our project:

- Separate access for consumers and staff.
- Consumer account information.
- Electricity bill viewing and billing history.
- Meter-reading and electricity-consumption records.
- Monthly consumption comparisons and simple charts.
- Basic highlighting of unusual consumption changes.
- Payment record viewing and payment status.
- Complaint submission and tracking.
- Complaint investigation and status updates by staff.
- Recording the outcome of complaints.
- Billing corrections by authorized staff.
- Staff dashboard and basic summaries.
- Sample data to demonstrate different situations.

### Optional Features

If we complete the main features and have enough time, we may also try to include:

- Uploading meter photographs or payment receipts as complaint evidence.
- Downloading or printing electricity bills.
- More detailed charts and consumption filters.
- In-application notifications.
- Simple estimated bill information based on clearly stated assumptions.

These features are optional and will depend on the time available for our project.

## 6. What the System Will NOT Do or Support

Since Enerlytics is a university project, we want to keep its scope realistic. Our system will not provide the following services:

1. **Real electricity distribution:** The system will not generate, transmit, or distribute electricity.
2. **Live meter connection:** It will not connect directly to physical electricity meters or automatically collect live readings.
3. **Physical meter inspection:** It will not send staff to a consumer's home to inspect a meter.
4. **Guaranteed fraud detection:** It will not confirm electricity theft, meter tampering, or fraud. It may only highlight unusual readings for investigation.
5. **Connection with official electricity companies:** It will not connect to the actual internal systems of electricity distribution companies.
6. **Real online payments:** It will not transfer money or connect to banks, cards, or mobile wallets. Payment records will be used for project demonstration.
7. **Automatic complaint approval:** It will not automatically approve complaints or change bills just because a consumer submits a dispute.
8. **Complete support for every electricity tariff:** It will use simplified billing rules for demonstration and will not cover every tariff, tax, subsidy, or policy used by all electricity providers.
9. **Guaranteed future bill prediction:** It will not guarantee the exact amount of a consumer's future bill.
10. **Electricity outage management:** It will not detect power failures, show live outage information, or control electricity restoration.
11. **Official legal decisions:** It will not replace official complaint authorities or make legally binding decisions.
12. **Separate full mobile applications:** Our initial project will focus on the agreed system prototype rather than fully developed Android and iOS applications.

## Conclusion

Through Enerlytics, we want to develop a system that brings electricity billing, consumption information, payment records, and complaint handling together in one place. We hope this will make it easier for consumers to understand their bills, monitor their electricity usage, and report billing problems.

We also want to make it easier for staff to review consumer information and handle complaints in an organized way. As a student project, we will focus on the features and situations described in this document and use sample data to demonstrate how the system is expected to work.
