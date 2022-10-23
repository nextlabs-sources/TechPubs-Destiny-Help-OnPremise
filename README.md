# README #

Please use following flag before you commit any changes to this repository. It will ensure to handle case sensitive file names. Specially files
generated from Rh tool.

# To replace help content #
1)	Remove all files/folders in the Help folder EXCEPT LandingPage folder
2)	Extract/Copy all files/folders provided by technical writer into Help folder
3)	Update URL value in destiny-base: HelpLocations_opl.properties, HelpLocations_opn.properties and HelpLocations.properties if required
4)	Update URL value in destiny-ui: config.js if required
5)	Check in these changes into BitBucket and trigger OnPremise help project build
6)	Trigger ServerApps project build

## git config core.ignorecase false ##