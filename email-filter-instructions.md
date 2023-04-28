Autoreply Option:

• i've noticed the templates menu doesn't show up sometimes try disable & renable in advanced settings or switching broswers.

	Gmail Inbox > Settings > Advanced
		
		Enable Templates
		
		Save Changes
		
	Compose a new email:	
		
		Subject: 
		
			Cease and Desist
		
		Body: 
		
			Dear Recruiting Firm,

			I am writing this letter to request that you immediately cease and desist sending emails, calling, and harassing people. Your actions are in violation of both US and EU laws, and any further contact from you will be reported to the appropriate authorities.

			Under the US Telephone Consumer Protection Act (TCPA), it is unlawful to make telemarketing calls using automated dialing equipment or prerecorded messages to residential phone lines without the prior express consent of the called party. Your repeated calls and messages constitute a violation of this law.

			Similarly, under the EU General Data Protection Regulation (GDPR), individuals have the right to protection of their personal data, including the right to object to the processing of their personal data for direct marketing purposes. Your persistent emails and calls constitute a violation of this law.

			Your actions are not only illegal but also a form of harassment that is causing significant distress to those affected. It is essential that you immediately stop all communication with the individuals concerned.

			Please be aware that we are keeping a record of all communications from you and will report your actions to the relevant authorities, including the Federal Trade Commission (FTC) in the United States and the European Data Protection Supervisor (EDPS) in the European Union.

			We strongly urge you to comply with this request immediately and refrain from any further contact.
			
	Click the 3 dot menu > Templates > Save Draft as Template > New Template > "Cease and Desist"

Filter Setup:    
	
	Gmail Inbox > Settings > Filters and Blocked Addresses

    Click Create New Filter (bottom of this page)

    In the Has The Words field, simply paste in the text from gmail-filter.md:

    [gmail-filter.md](https://github.com/SirKratosAurion/ITJobSpam/blob/d07465256333588b47ec944c1dfd0425de0e3651/gmail-filter.txt)

    Click Create Filter

    On the next page select the following:
	
		With Autoreply: (because gmail wont autoreply if you delete them)
			Skip the inbox (Archive it)
			Apply the label (create a new label called recruiter spam or something)
			Send template: Cease and Desist
			Never mark it as important
			Also Apply filter to XX matching conversions
	
		Without Autoreply:
			Delete It 
			Also Apply filter to XX matching conversions

    Click the big blue Create Filter button and your done.

Original by: u/Elranzer
Updated by: u/sirkratosaurion