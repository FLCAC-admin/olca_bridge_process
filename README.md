Scripts to create bridge processes in openLCA

## Bridge Processes
1.	Export all flows (as JSON-LD) for bridging and import to a new database in openLCA (not connected to Collab server)
2.	Copy+paste the Python script into openLCA Python developer screen
3.	Change file path to csv file with bridge process information
4.	Make sure unit nomenclature in csv matches exactly that of openLCA. Remove location field
5.	Make sure no commas in numbers (change numbers to general format)
6.	Run script in openLCA
7.	If no error, close database and reopen it
8.	Processes in the database should now show bridges
9.	Export bridge processes and import to the main CDD collaboration server database
10.	Save in separate folder (e.g., "CDD to USEEIO")

## Elementary Flow List
1.	Select `Window > Flow Mapping (Experimental)` in v1.9
2.	Select JSON-LD file for CDD mapping to Federal LCA Commons flow list
3.	Will display flow mapping window
4.	Select `Apply` and check all three boxes
5.	Manually delete empty flow folders
