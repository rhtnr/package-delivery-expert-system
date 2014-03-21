README
======


This is a package delivery simulation expert system programmed using CLIPS.
A truck is required to drive the shortest route to the
pickup city, pick the package up, drive the
shortest route to the destination, deliver
the package, then drive the shortest rout
e back to Orlando to wait for the next
shipping order.

Main Exec File: SOURCE.clp
City data:cities.txt
Truck data: trucks.txt
Package data: packages.txt



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
