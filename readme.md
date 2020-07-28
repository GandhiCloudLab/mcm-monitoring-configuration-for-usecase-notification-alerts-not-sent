# MCM Monitoring Configuration for usecase - Notification Alerts are not sent

MCM leverages the following objects for Application Monitoring and Incident management.
- Thresholds
- Runbooks
- Event Policies
- Incident Policies

This document explains about how to create and configure those objects for an use case `Notification Alerts are not sent`.

Here is the usecase and incident handling flow.

<img src="images/027-notification-flow.png">


## 1. Incident - Notification Alerts

We are going to create and configure the following.

- Threshold for `MQ Queue Not being Read`
- Threshold for `Notification Saturation High`
- Runbook for `Notification Runbook`
- Event Policies for `MQ Queue Not being Read`
- Event Policies for `Notification Saturation High`
- Incident Policies for `Notification Alerts`

Here is the sample incident with events and runbook.

#### Incident Summary

<img src="images/022-incident-notfication-inbox.png">

#### Incident Details - Notification Saturation High

<img src="images/023-incident-notfication-event-saturation.png">

#### Incident Details - MQ Queue Not being Read

<img src="images/024-incident-notfication-event-mq.png">

#### Incident Details - Runbook associated
<img src="images/025-incident-notfication-runbook.png">

--------

## 2. Goto Administration Page in MCM Console

Click on the `Infrastructure Monitoring`

<img src="images/001-menu.png">

--------

## 3. Configuring Threshold

#### Goto Threshold Page

Click on the `Threshold` card

<img src="images/002-card-threshold.png">

#### Create Threshold for `MQ Queue Not being Read`

Here is the list of threshold created. You can click on `Create` button to create new.

<img src="images/003-threshold-home.png">

Here is the threshold configuration for `MQ Queue Not being Read`.

Enter the parameters as highlighted.

<img src="images/004-threshold-mq-1.png">
<img src="images/004-threshold-mq-2.png">
<img src="images/004-threshold-mq-3.png">
<img src="images/004-threshold-mq-4.png">

#### Create Threshold for `Notification Saturation High`

Here is the list of threshold created. You can click on `Create` button to create new.

<img src="images/003-threshold-home.png">

Here is the threshold configuration for `Notification Saturation High`.

Enter the parameters as highlighted.

<img src="images/005-threshold-saturation-1.png">
<img src="images/005-threshold-saturation-2.png">
<img src="images/005-threshold-saturation-3.png">

--------

## 5. Configuring Runbook

#### Goto Runbook Page

Click on the `Runbook` card

<img src="images/008-card-runbook.png">

#### Create Runbook for `Notification Runbook`

Here is the list of Runbook created. You can click on `Create` button to create new.

<img src="images/008-runbook-notification-1.png">

Here is the Runbook configuration for `Notification Runbook`.

Enter the parameters as highlighted.

<img src="images/008-runbook-notification-2.png">

--------

## 5. Configuring Event Policies

#### Goto Event Policies Page

Click on the `Policies` card

<img src="images/030-card-policies.png">

#### Create Event Policies for `MQ Queue Not being Read`

Here is the list of event policies created. You can click on `Create` button to create new.

<img src="images/010-event-home.png">

Here is the Event Policy configuration for `MQ Queue Not being Read`.

Enter the parameters as highlighted.

<img src="images/012-event-mq-1.png">
<img src="images/012-event-mq-2.png">
<img src="images/012-event-mq-3.png">

#### Create Event Policies for `Notification Saturation High`

Here is the list of event policies created. You can click on `Create` button to create new.

<img src="images/010-event-home.png">

Here is the Event Policy configuration for `Notification Saturation High`.

Enter the parameters as highlighted.

<img src="images/013-event-saturation-1.png">
<img src="images/013-event-saturation-2.png">
<img src="images/013-event-saturation-3.png">

--------

## 6. Configuring Incident Policies

#### Goto Incident Policies Page

Click on the `Policies` card

<img src="images/030-card-policies.png">

#### Create Incident Policies for `Notification Alerts`

Here is the list of Incident policies created. You can click on `Create` button to create new.

<img src="images/014-incident-home.png">

Here is the Incident Policy configuration for `Notification Alerts`.

Enter the parameters as highlighted.

<img src="images/015-incident-notification-1.png">
<img src="images/015-incident-notification-2.png">
<img src="images/015-incident-notification-3.png">
