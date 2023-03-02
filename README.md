# ideas-dev

WORK ITEM TEMPLATE

Requirement/User story: 
Desired business value if applicable:
Details/scope [include any COPY or styles requirements if not explicitly clear/stated in the next item]:
Design docs, images, source/link:
 
Pre-Code Consistency check [not reinventing the wheel or breaking app wide pattern]: 
•	 make sure these states/style patterns are the same, if desired to be (check with design), for all parts of the app.
•	Check for global reusable styles and components. 
 
 
Q: What event(s) is (are) expected to trigger the "expansion" in each viewport mode/device?
 
Possible events:  Here is a list of the possible UI events for reference: https://developer.mozilla.org/en-US/docs/Web/API/UI_Events 
 
DESKTOP:
MOBILE:
Other specific sizes (note the px size for media query) like Tablet if applicable:
BOTH:
 
 
Q: What are the expected states related to this user action [can also be stated as the how to "handle" user input & events]?
 
Are the CURRENT states to be changed at all if NOT new? If so, each item would be split in 2 columns. 
DEFAULT STATE:
SUCCESS: 
LOADING STATE:
ERRORS STATES/UNKNOWN:
ACCESSIBILITY Requirements:
Translation Considerations:
Data Persistence Considerations [Refresh, session expiry, leave page/tab come back]: 
OTHER STATES [this should cover ALL edge cases even if stating to not worry* in certain cases]:
 NOTE: not all states will be applicable to certain components. State can refer to text, or visual cues/style.
 
CAUTIONS/GOTCHAs or related work worth mentioning:
 
 
Ticket language TIPs:
Work with FA for how to make it universal for business and developer. Shoot for a balance precision, concise, simplicity and technical jargon.
 
What is "Done"? Or acceptance criteria 
See here https://www.productplan.com/glossary/acceptance-criteria/  Are the Acceptance Criteria testable?
If so, what aspect of (automated) tests can be done by devs and what part by Quality Assurance for example. 
 
OPTIONAL- ICS Principles Check [mainly ask just ONE or more of the principles and communication guide stuff]:
Is this solution simple? Is there reason to being up something seemingly out of alignment.

RASCI [who can make decisions for what aspects or contact for who to turn for help]:
Change Process: If anything above changes do this…. Who notates?  What type of things are REQURIED to be notated?

*-there is something to be said for level of sophistication of the required solution. User expectations are important to manage so there can be something noted if not covered as to maybe future enhancement. This preplanning will prevent needless questions that always surely can come from each developers experience as to how something "should behave."



*-there is something to be said for level of sophistication of the required solution. User expectations are important to manage so there can be something noted if not covered as to maybe future enhancement. This pre planning will prevent needless questions that always surely can come from each developers experience as to how something "should behave"![image](https://user-images.githubusercontent.com/102767761/222252691-6a5d5281-00b3-4c9f-a5b7-2c0e87b4ad07.png)
