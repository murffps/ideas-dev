# ideas-dev

User Story: 
Implementation Requirement: 
Details: 
Edge Case: if applicable 
SOURCE (design or related):


USER CASES for consideration in acceptance criteria 

Requirement/User story:  as you select the address, all the other fields appear, populated.

Q: What event(s) is (are) expected to trigger the "expansion"?

Possible events:

DESKTOP:
	Enter - Fetchify does NOT allow ENTER to work but currently ours allows ENTER to exit the tool and go to the next input
	
	Mouse click the desired address 
	
MOBILE:

	Tap
	
BOTH potentially:
Interacting with AUTO FILL from either Browser keychain tools or phone stuff

	
Q: What are the expected states related to this user action?
SUCCESS: 
ERRORS STATES:
Currently … vs… desired 
UNKNOWN/DEFAULT/ LOADING STATE


OTHER STATES or EDGE CASES or ACCESSIBILITY Concerns:
	A. They decide to go back to the top and retype the street address. Expected behavior would be to keep the expansion open and replace all the other data I all fields if a new address is selected. 
	B. Type full address and NOT choose and address - how to handle white space, comma and formatting excess info like ZIP if not required in that field …

	A. What if they don’t see their address ? Not sure if we are handling error states in that case- US vs the default  integration error state 
	B. LANG (mostly NA minus for Arabic type stuff) 



EFFORT level:
1. fancy 


5. least fancy 
DEFAULT most common user expectaions .. ex: notificaitons in an app that needs them 




CAUTIONS: with integrations they usually need to be tested in close to as prod possible


![image](https://user-images.githubusercontent.com/102767761/221994224-8320aaf7-7895-45ce-b773-db6ec7f5fdf5.png)



NOTES incomplete thoughts 
Basing things on events ?
Or style
Feature description and or Purpose: We want to capture the street address and then expand 
	A. Speed
	B. Accurate and/or Correctness

In the spirit of Writing up docs and pseudocode PRE coding 

TYPE
UI Event based
FORMS

CLICKS etc 

Diff process slightly maybe 

LOG for GOALS  to update in @work

	1. Touch base with Jode over edge cases 
	- ENTER key with incomplete 
![image](https://user-images.githubusercontent.com/102767761/221994289-e9bcb834-2f45-4d09-848b-008fa0d22b01.png)
