---
description: QUESTIONS ABOUT ALERTING
---

# Alerting

## What is the difference between alert and special alert?

**Alert**: An alert is an email information about an incident that has possible effects on travellers, sites or business activity. Alerts are related to a specific traveller or a company site location. For each incident that triggers an alert, the system sends different emails – one is tailored to the traveller, the other is tailored to the travel manager. 

**Special alert**: In the event of a special alert, it cannot be ruled out that a traveller is directly affected by a security incident that can pose a threat to life and health. The platform directly contacts affected travellers via phone call in order to detect their status. In addition, the traveller receives the incident information via email, including behavioural guidelines to reduce the risk in the vicinity of the event. For each incident that triggers a special alert, the system sends different emails – one is tailored to the traveller, the other is tailored to the manager and includes continuous status updates.

{% hint style="info" %}
 Please view template examples of alerts and special alerts in the follwing pages.
{% endhint %}

## Why does traveller A receive a special alert status call, while traveller B right next to him receives only an alert email?

There can be different reasons for a situation like that, for example: 

**Scenario 1**: Assuming traveller A and B are at a conference together, but the location confidence of both travellers is different. While the platform only received PNR data with the arrival airport of traveller A, traveller B used the calendar tracking feature and added the exact location of the conference venue. As a result, the platform has more precise travel data for traveller B than for traveller A and hence, determines a larger incident radius for traveller A. While the system can exclude traveller B to be inside the impact radius of the incident that triggered the alerting, it has less precise information for traveller A and thus, in order to find out, if he needs help, triggers the automated status calls 

**Scenario 2**: Traveller A and B are again at a conference together, but work for different companies, both using the platform. It is highly likely that the alerting settings of both companies vary largely. Company A may be risk-averse, while company B is more prepared to take risks. That means the alerting settings of company A allow for a large number of special alerts, also including incidents with rather moderate severity. Company B on the other hand, prefer to trigger the status detection process and have their travellers called only in the event of critical incidents. These two scenarios shall explain that several parameters determine the incident radius. Among the strongest parameters shaping the radius are the incident impact, the incident category and the traveller location confidence. If you are uncertain about your settings or just curious, how the platform works, you can check and see in the section called “incident radius preview” in the alerting settings of the travel monitor.

## How can I see the alerts and special alerts in the travel monitor?

Special alerts are visualised as icons with a red frame. Alerts are visualised as icon with a yellow frame. You also can use the filter to find a specific alert or special alert.

## I have 200 travellers in Shanghai. If a critical security incident occurs, how long does it take until I know the status of my travellers?

As soon as the platform detects the incident and it has been verified by the analyst \(generally, the verification takes 1-2 min.\), the platform will immediately start calling your travellers. If you defined in the call settings that your travellers would be called ONCE, you would receive a final status of all 200 travellers within 1-2 minutes. However, usually, it is preferred to have more call attempts as most of the time your travellers will not answer at the first call. 

{% hint style="info" %}
 For more information, please see the section alerting settings.
{% endhint %}





