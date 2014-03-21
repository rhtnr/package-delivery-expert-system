README
======


Name: Rohit K Nair
UFID: 4698-3602



	Question: How to Execute the source?

		ANS:    I have made is really simple to execute the source.
				All data for cities, trucks and pakages are stored in files cities.txt, trucks.txt and packages.txt
				These file should be in the same folder as the SOURCE.clp file.
				Then the CLIPS IDE is opened and everything is cleared using (clear)
				Then the SOURCE.clp file is loaded into CLIPS IDE and reset is fired using (reset)
				Now the SOURCE.clp rules are run using (run).
				Now the output can be awaited.
				
				(Please do not modify the structure of input files as the program depends on the file structure to read data
				consistently. The structure in the input files are exactly as same as in the Question PDF. Any changes to the files
				should therefore retain the structure in the Question PDF)
				
				THEREFORE THE COMMANDS THAT SHOULD BE EXECUTED ARE AS FOLLOWS:
				
				
				         CLIPS (Quicksilver Beta 3/26/08)
			CLIPS> (load "SOURCE.clp")
			CLIPS> (reset)
			CLIPS> (run)
			
			
			
			
			
			
			
			
			
=====END OF README=====