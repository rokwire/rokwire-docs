



# this is a huge header #
## this is a smaller header ##
### this is even smaller ###
#### more small ####
##### even smaller #####
###### smallest still: `<h6>` header

# Writing Style Guide
	
### TERMS 

    Let's borrow formatting and rules from Apple Style Guides where applicable.
    * Apple: https://help.apple.com/applestyleguide/?fbclid=IwAR0OlHl0mvq0Omz6rpKRVMoQ5675F8QkTqaR7MgqyofeRFUeX_Gnec9s2aU#/apsg72b28652
    * Human Interface Guidelines https://developer.apple.com/design/human-interface-guidelines/

    Below is an example of how they format elements such as *definition*, _usage example_, _"don't use" rules_, _correct/incorrect examples_. Note also that italic and not quotation marks is used to refer to the word as a word. (<- rephrase this)

**Mac Catalyst** A feature of Xcode that developers can use to bring iPad apps to Mac as native Mac apps. Don’t use *Catalyst* alone. Developers bring apps to *Mac*, not to *macOS*.

> Bring your iPad app to Mac with Mac Catalyst.

Don’t use *Mac Catalyst* as an adjective. For example, don’t describe an app as a *Mac Catalyst* app; say a *Mac app created using Mac Catalyst*, or similar. Apps don’t *run in* Mac Catalyst; apps are *built with* Mac Catalyst.

> *Correct:* Mac apps built with Mac Catalyst can use AppKit APIs marked as available.

> *Incorrect:* Mac apps running in Mac Catalyst can use AppKit APIs marked as available.

**Style for User Guides**

Each user guide can have its own style conventions. But there should be some consistency so that writers don't get confused.

The followign example could be a guide for conventions to use in user guides. Note: this is not from Apple.
* Use italic and > chains for "go to" menu sequences.
* boldface button names

    6. Once you’ve connected to your HubSpot account, you can configure the forms, pop-up forms, and live chat features.
    
    * **Forms & Pop-up Forms:** In your WordPress dashboard, go to *HubSpot > Forms* and click the **Create form** button (as shown in the image below) to create a form or a pop-up form. Or in your HubSpot account, go to *Marketing > Lead Capture > Forms* to create your form or pop-up form.

_________________________________________________________________________________________________________


**TERMS**

**Capability** (See Rokwire Taxonomy - contrast w/ "features")


**Rokwire** is an open-source software platform for building a variety of mobile services based on easily connected data streams. The Illinois app and Safer Illinois are two mobile products built on the Rokwire platform.

Possible uses: *Rokwire Initiative* and *Rokwire Platform* and *Rokwire Community*\
Question: Try not to use Rokwire by itself, but as a modifier ?? Or, when used by itself Rokwire refers to the software platform; when describing an organization or work project, Rokwire can be used as an adjective: Rokwire initiative, Rokwire project. 

Multiple organizations are associated with the Rokwire project.

University of Illinois
- Smart, Health Communities Initiative
- Technology Services has administrative responsibility for operations of the Rokwire "Illinois Instance" at UIUC. 
- The Illinois Instance
- The Illinois App Steering Committee has decision making authority over the Rokwire Capabilities that are selected to be deployed in the Illinois app.


Incorrect spellings: Rockwire. RokWire. Don’t refer to the _Illinois_ app or the _Safer Illinois_ app as *Rokwire*.

**Illinois** The _Illinois_ app is a mobile app that incorporates a set of information
services focused on life at University of Illinois. The app includes features about
campus events, Illini sports and a number of resources for students including dining
information and laundry services.

_AVOID:_ Don’t call the Illinois App “Rokwire”. 
*Questions:* Can we say "Illinois app" without "the", "Illinois" without "app"? Or should it always be styled "the Illinois app"?

**Safer Illinois**
_AVOID:_ Safer in Illinois. Covid App.

NetID - Note Capitalization. NetID is an identity credential assigned to students, faculty, staff
and certain other affiliated registered individuals at the University of Illinois. The NetID is recognized on all
University of Illinois campuses. With the associated password, the NetID is the login to most
University computing and networking services

**OSF HealthCare** Note capitalization. This is the style requested by OSF.
**McKinley Health**
**Counseling Center**
**Bluetooth** Always capitalize.

.....
login and related. (Some parts based on Apple Style Guide)

* login (n., adj.), log in (v.)

Use to refer to the procedure for authenticating a NetID. Don't use within apps; use _sign in_ instead.

log in to , not log into.

Correct: You must log in using your NetID.

Incorrect: You must log into the single sign on place.[Note: let's add an entry for SSO and single-sign on. With a note to avoid using the acronym SSO, because people don't know what it means.]

More usage: Users log in to a file server (not log on to ); users log out of a file server (not log off , log off of , or log out from ).

Correct: You must log out of the server.

Incorrect: You must log out from the server.

Incorrect: You must log off the server.

Use _login dialog_ box to refer to Shibboleth single-sign on interface. [I think?]

Don't use log on, log off; use log in and log out.

See also sign-in (n., adj.), sign in (v.).

**Period** See End Punctuation.

**End Punctuation** All image captions and callouts should end in a period, even when the callout is an incomplete sentence (for consistency). Don’t use end punctuation in headlines, headings, subheadings, UI titles, UI text, or simple lists (three or fewer words per item). 

 **Questions:**

 * When should statements in text screens end with a period? Any time they are a
 complete sentence?
 * An inline heading could have end punctuation.

 **Example.** This is an example of a paragraph with an inline heading.

## Capitalization in App Screens

Each App can have its own style rules for text. On the precedent of our current practices in Illinois and Safer Illinois apps, we have derived the following guidelines.

* Buttons use title case.
* Screen Titles use title case.
* Commands in screens use sentence case.
* Section headings in screens use sentence case.
* Drop-down menus use title case.

Give examples.

## Illinois and Safer Illinois Style Guide

**Exposure Notification and Exposure Notification system** – Capitalize Exposure Notification as a proper noun when referring to the feature. Do not capitalize “system”. Use lower case when referring to the notification message itself.  

 I just received an exposure notification from the Exposure Notification system.

sign-in (n., adj.), sign in (v.) Sign in – Use sign in sign-in when referring to the verb and noun that describes entering your credentials to authenticate your user identity in the app. The hyphen should be used only when referring to the noun. Do not use *log in* or any of its variants in relation to use of the app.  

> I signed in to the Safer Illinois app using my sign-in credentials.  

**QR code** (Quick Response) Encrypted key, secret key, qr code, etc. Need consistent wording 

**Privacy Statement** (used in app), Privacy Notice (used in privacy agreement), Privacy Agreement (not used, but should be?) Make consistent. The official full name is Mobile Privacy Notice (MPN).

**Non-University member.** Capitalize both N and U. Hyphenate. (double-check w style guides) 

**i-card** – Use this word specifically to describe the physical University of Illinois identification card. UIN refers only to the student identification number. Do not capitalize any part of this word, and always include a hyphen.  

> Incorrect: iCard, i-Card

**Status Card** – capitalize [define this term]

## Guidelines for Writing

* Avoid the use of exclamation marks.
* Whenever possible, image captions and callouts should be complete sentences. 
* Write in a conversational style. Use short, simple sentences. Divide complex sentences. Sentence fragments can be OK.

## Accessibility
To facilitate screen readers, observe the following guidelines.

* Provide alt text for all images.
* Embed hyperlinks in a noun or noun phrase rather than displaying the URL in the text.
[please add to this list]

## Concepts

**Contact Tracing** Contact tracing is a public health procedure used to identify people
who may have come into contact with an infected person. Conventional contact
tracing suppresses the spread of disease by finding infected people and isolating and
treating them. The public health workers who conduct contact tracing interview known
infected individuals, attempt to find all recent contacts with the infected individual, and
then follow up with those contacts with testing, isolation, treatment and other
measures.

The Safer Illinois app uses Bluetooth technology in an anonymous process that lets
people know if they have recent come into contact with a person who has been
diagnosed as being infected with the disease. The Illinois app does not do contact
tracing, because the Illinois app has no way of identifying individuals who are using the
app.

_AVOID:_ When describing the exposure notification capabilities of the Safer Illinois
app, do not use “contact tracing”, “digital contact tracing”, “track-and-trace”. Instead,
use “digital exposure notification” or “exposure notification”.


**Safer Illinois App Description**

**Short Version**
Safer Illinois is the official COVID-19 app for Champaign County residents and the
University of Illinois. The app provides pandemic resources to support community
health and safety.

**Long Version**
Safer Illinois is the official COVID-19 app for Champaign County residents and the
University of Illinois. The app provides pandemic resources to support community
health and safety.

* The app allows you to retrieve your virus test results, manage future tests, and make contact with health response teams and health care providers.

* You can use the app to access information about test locations and COVID-
guidelines for your county.

* A symptom scale supports automated self assessments.

* Exposure notification warns of possible contact with infected individuals through anonymous proximity tracing.

**Ideas and phrases used in the Safer Illinoi app.**

Join the fight against COVID-19. Track and manage your health to help keep our Illinois
community safe.

You can use this app as your companion in your fight against COVID-19.

Help stop the spread of COVID-19 by following these current guidelines.

**Other Phrases:**

Diagnostic test - don't use.

Anonymous proximity tracing

confidential proximity detection (currently we use this phrase in FAQs)


Quarantine vs Isolate: A couple of wording issues. Because Derrick tested positive, he’ll
have to isolate rather than quarantine. I know, it sounds like the same thing. You isolate
(by yourself) if you’ve tested positive. You quarantine if you’ve been exposed but have
not tested positive. In quarantine, you can be with others (I think).

Also, we have been told not to use the terms dorm or dorms. We are to call these
places residences or campus housing or mini estates or some other euphemism.

Use tap, not tap on


**Rokwire Taxonomy terms**

* Capability is this an internal developer term or a public term?
Internal developer term. It should refer to third party processing systems, such as Converge. (per Sandeep 2/5/21 - but check.)

* Health Center Building Block Health Center Building Block is a ....^

* Preferred public-facing term: ??^

* Data Store (could be secure database server)^

* Feature^

* Are there standard names for menus, panels, screens in app user interface^

**Reference**

Screen on Illinois App:
“Help keep Illinois safe. Join the fight against COVID-19 by tracking and managing
your health.”

Cf. Rokwire Taxonomy


# Notes from Others

Shontz, Douglas <dshontz@uillinois.edu>

All,

The FDA regulates anything that provides a diagnosis or guidance for treatment of a medical condi;on as
a “medical device,” and this includes so>ware. All FDA-regulated medical devices must have FDA
authoriza;on.

This is reason to remove any use of the word “diagnose” or “treat” from these so>ware packages. They
are not FDA-approved medical devices.

So the answer to the ques;on is, yes, using these terms in an unapproved medical device could create
liability for the University. There is interpreta;on involved in what’s considered a medical device and
what isn’t, so it’s not always clear cut. However, comparing the ease of changing a few words with the
poten;al risk to the University, this should be an easy call to stay well away from any indica;on that this
so>ware could be interpreted as a medical device.

Happy to clarify further on any points.

University Affiliate. Affiliates are predefined groups that are closely related to the university and
have been granted access to digital resources and therefore have a NetID with certain access
privileges. Also, it is useful to understand that UINs are simply an id number that carry no
access credentials of and by themselves. A NetID is a credential.

## - Greg Gulick

**Other Terms**
Secret (represented by QR code):

## - Credential stored as an encrypted environment variable

- (or) encrypted credential
https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html#intro-getting-
started

Operations: Operations is anything supporting an ongoing effort, e.g., business management and business infrastructure. Support, infrastructure. 

Development: Development is the other dimension for Rokwire project.

Smart Healthy Communities Initiative: Not "Community"

Version numbering for documentation: Use semantic versioning. Three digits (Major.Minor.Patch). 
Work in progress is indicated by a major number of zero (0.1.0) and also by pre-release tags alpha (a) and beata (b) and release candidate (rc). A build sequence might look like this: 0.5, 0.6, 0.7, 0.8, 0.9 → 1.0b1, 1.0b2 (with some fixes), 1.0b3 (with more fixes) → 1.0rc1 (which, if it is stable enough), 1.0rc2 (if more bugs are found) → 1.0.

Time stamp for documentation: 
