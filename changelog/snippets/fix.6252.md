- (#6252) Fix the blueprint fire rate test not accounting for rounding tie-breaking towards even numbers, which gave incorrect suggestions for these numbers:
	- 4.0 fire rate: suggested 3.333, correct suggestion 5.0
	- 0.8 fire rate: suggested 0.769, correct suggestion 0.833
