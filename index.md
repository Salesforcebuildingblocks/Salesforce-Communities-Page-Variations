## Page Variations

Page variations are alternative versions of a page. You can use them to try out different page layouts and styles, or create variations that are aimed at distinct audiences. Every page in your community, including custom pages, must have one default page variation. You can add as many extra variations as you need on the page’s Page Variations tab.

You can also duplicate page variations, which really speeds things up when you’re creating page variations that have only minor differences.

Assigning specific audience criteria to a page variation lets you target a particular set of members. Criteria include:
Profile
Location
Record type
You can add multiple profiles to a variation if you like, or none.

Here are some considerations when setting location criteria:
Location based on the user’s IP address, which could potentially be located in a neighboring city.
The location permission is not on by default in Developer Edition orgs. Contact Salesforce if you want to use this feature in that edition.
Location criteria don’t work in countries that don’t allow the use of the Google API.

Let’s say you have a financial services community and you want your clients and your brokers to see a different Home page based on their profile. You can create two variations of the Home page, each with content targeting a specific audience—clients and brokers in this case—and set the visibility of each page to different profiles. All members go to the same URL, but your clients see Home A, whereas your brokers see Home B.

# Who Exactly Sees What?
After you create the page variations you need in Page Manager, you can set their visibility. Choose from three visibility options that, when combined with a page’s published status, determine whether a page is visible to your community members.

Default: All users unless set by profile
When the page is published, it’s visible to all valid community members, except members whose profiles are assigned to a different page variation. Each page must have one default page variation.
By Profile
When the page is published, it’s visible only to users with the selected profiles.

New Changes 2
