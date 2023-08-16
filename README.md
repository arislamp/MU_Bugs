# MU_Bugs

General Fixes :

- Navbar Search
	Single Word Search working. Adding 2 more search words, not working.
- Translations must be everywhere

Homepage :
	
	- Infinite loading logo in hero
	- On page load getting 500 Server Error ( https://staging-mu.monsterenergy.com/partial/dashboard.partials.assignments?current_url=%2Fdashboard )
	- Recommended Content - Events view more linking to /dashboard
	- New Content - Events view more linking to /dashboard
	- Events - Events view more linking to /dashboard
	- Hero Slider getting js error when changing slides :  TypeError: Cannot read properties of null (reading 'muted') js error

Tickets :

	- When submitting a form all fields in all tabs become required. Each form should submit separate ?.

Submit-ideas : 
	Nothing so far
 
Faq :
	Nothing so far

Settings (My-Profile) :

	- Upload avatar photo not working ( 403 Forbidden )
	- Edit Profile Modal : Should First Name | Last Name | Email etc be editable? atm some fields are not editable
	- 10 OF 15 ASSIGNED CONTENT COMPLETED hard coded
	- badges earned not showing
	- MY INTERESTS | COMPETENCIES | HARD SKILLS -> hard coded values
Guided Help :

	- Live chat not working

Settings (My Interests) :

	- At the final step Review/Submit when clicking the button Confirm/Submit getting error in console :
 		The POST method is not supported for route settings/my-interests. Supported methods: GET, HEAD.

Settings (My Notes) :

	- Clicking on some of the videos getting error :
 		Non-static method App\\Models\\Content\\Event::isRsvp() cannot be called statically
        - Clicking SortBy getting error :
		Order direction must be \"asc\" or \"desc\
Settings (My Notes) :

	- Upload Document not working getting the following errors :

 		- "League\\Flysystem\\Filesystem::read(): Argument #1 ($location) must be of type string, null given
   		- InvalidAccessKeyId</Code><Message>The AWS Access Key Id you provided does not exist in our records.
Badges :
	Nothing so far

Reports :
