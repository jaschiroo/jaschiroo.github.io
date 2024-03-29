---
layout: post
title: "Design Sprint: St. Paul Parking Permits"
date: 2017-03-19
categories: design-sprint
---

This exercise was a 1-hour sprint to practice the UI design process.

It was motivated by the parking permit process for residents of 29 designated permit areas in St. Paul. The purpose of this system is to make sure that non-resident cars are not parked in these zones for extended periods of time. Right now to get a permit residents must apply in person at the Traffic Operations Building that is only open 7:30 am - 4:30 pm M-F, which is a difficult window for people with jobs. This process ends up being frustrating at the very least.

I redesigned the UI of the website to allow for online permit applications, in order to improve the process of getting a permit. This system needs to establish that an applicant lives in a permit zone, and record residency information, vehicle information and take payment. From the resident's perspective, it needs to be easy to see if they need a permit, and flexible enough to accept the residency and vehicle information that they have on hand. Residents want to be able to apply for or renew their permits online at their convenience. Permit enforcement wants residents to have current permits placed correctly on their vehicles to make enforcement easier.

<img src="/images/sprints/parking-permits/map-search.png"
    alt="Search for address"
    style="max-width:90%;height:auto;border:1px solid black;" />

 Residents begin by entering their address to either find their zone or find out that they do not need a permit.

 <img src="/images/sprints/parking-permits/map-results-permit.png"
     alt="map result - permit needed"
     style="max-width:90%;height:auto;border:1px solid black;" />

<img src="/images/sprints/parking-permits/map-results-no-permit.png"
     alt="map result - no permit needed"
     style="max-width:90%;height:auto;border:1px solid black;" />

Applying for a permit requires residency information, most often confirmed by driver's license. Since residents may be applying for a permit because they recently moved to the zone, they need the option to provide further proof of residency.

<img src="/images/sprints/parking-permits/permit-app-residency-2a.png"
    alt="residency entry screen"
    style="max-width:90%;height:auto;border:1px solid black;" />

For renters a lease, utility bill or notarized statement can be used to establish temporary residency in the zone which will need to be reviewed by hand.

<img src="/images/sprints/parking-permits/permit-app-residency-3a.png"
    alt="Residency verification selection"
    style="max-width:90%;height:auto;border:1px solid black;" />

Once residency can be verified, the applicant moves on to the next section.

<img src="/images/sprints/parking-permits/permit-app-residency-4.png"
    alt="Upload residency document"
    style="max-width:90%;height:auto;border:1px solid black;" />

Vehicle information can be confirmed by title or registration number, uploading an insurance card, or the VIN. The VIN provides vehicle description, or it can be entered manually.

<img src="/images/sprints/parking-permits/permit-app-vehicle.png"
    alt="Vehicle information"
    style="max-width:90%;height:auto;border:1px solid black;" />

After they have entered their residency and vehicle information, they might need the option to add another permit or a special permit.

<img src="/images/sprints/parking-permits/permit-app-add-another.png"
    alt="Permit summary page"
    style="max-width:90%;height:auto;border:1px solid black;" />

If they select to add other permits, it takes them through the registration process for those permits. Otherwise, applicants pay for the permits they selected.

<img src="/images/sprints/parking-permits/permit-app-payment.png"
    alt="Payments page"
    style="max-width:90%;height:auto;border:1px solid black;" />

After paying, they see a confirmation screen that gives them a processing number for trackability, an estimated timeline, and the option to receive updates. Transparency in a government system like this builds trust with users.

<img src="/images/sprints/parking-permits/permit-app-finish.png"
    alt="Successful submission screen"
    style="max-width:90%;height:auto;border:1px solid black;" />

Once residents receive their permits, they also get an instruction diagram visually describing how to place the permit on their vehicle. Visual instructions help to reduce confusion and increase compliance by mapping directly to the user's context.

<img src="/images/sprints/parking-permits/permit-instructions.png"
    alt="Permit placement diagrams"
    style="max-width:90%;height:auto;border:1px solid black;" />

If a resident were to have selected to purchase other permits, they would select the type and number of each, shown the total and summary screen, and pay for the special permits.

<img src="/images/sprints/parking-permits/other-permits.png"
    alt="Special permit selection screen"
    style="max-width:90%;height:auto;border:1px solid black;" />

They would receive a similar confirmation screen, along with a diagram for placement upon receiving their special permits.

<img src="/images/sprints/parking-permits/other-permits-instructions.png"
    alt="Special permit placement diagrams"
    style="max-width:90%;height:auto;border:1px solid black;" />

For current residents seeking to renew their permits, the process is streamlined, since their information is already entered. They first search for their existing permit by name, number or address.

<img src="/images/sprints/parking-permits/permit-renewal.png"
    alt="Permit renewal screen - search for permit"
    style="max-width:90%;height:auto;border:1px solid black;" />

The system finds their record, and they are prompted to confirm or add a new permit.

<img src="/images/sprints/parking-permits/permit-renewal1.png"
    alt="Existing permit search results"
    style="max-width:90%;height:auto;border:1px solid black;" />

Finally, they reach the payment screen and confirmation page as with the permit application, and receive an instruction diagram with their renewed permits.

This redesigned UI makes it easier for residents to apply for and renew their permits for the St. Paul parking permit zones. I made assumptions in this design sprint, including the ability of staff to access information such as property tax information, drivers license numbers, title and registration numbers and VINs. I also assumed that as in the current system employees will be able to verify uploaded documents to check residency and vehicle information.

Since this was only a 1-hour design sprint, there are several aspects that I wasn't able to address. Handling the processing and enforcement of these permits is one, with different sets of users completing those tasks who have different needs. The resident process may depend on capabilities of the processing procedure in ways that I did not explore. I also limited myself to redesigning the UI, without taking a look at the user experience of this system - the permit system as it exists now may not be the best way to solve the problem of non-resident cars parked on residential streets for long stretches.
