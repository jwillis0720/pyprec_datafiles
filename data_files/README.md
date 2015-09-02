#PyPrecursor

There are two input tabs. Use one or the other.

1) Input Options
	
	V Family - V gene family to search by
	V Gene - Specific gene to query
	D Family - D gene family to search by
	D Gene - Specific gene to query
	J Family - J gene family to search by. Note that there are no specific sub genes.

	Verbose - Will output each match
	Output File - The output fasta that the matches will write to
	HCDR3 Length - Find precursors that equal this length
	Login User Name - The user name of the Mongo Database 
	Login Password - The password of the Mongo Database

	HCDR3 Pattern (Regex)
	You can leave each option blank to search for all amino acid identities at that position, or you can use comma seperated amino acids to search only those identities (e.g A or A,C for alanine or alanine cysteine at a given position). It must either be a single character or characters that are comma seperated.

2) Advanced Options

	You can use greater than or equal to an HCDR3 length.

	Advanced Regex for HCDR3 - If you know Regex, type in your own regex here without the quatations. Ex. .*[DVQ][YKDHY][GRVY][DY]Y[YVL][TSY][?GQN][ML][DGE][VLF]$.


MAKE SURE YOU PRACTICE QUERIES ON PRACTICE DATABASE FIRST BEFORE USING ONE OF THE DONORS