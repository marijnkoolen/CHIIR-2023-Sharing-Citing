all-data.tsv		Cleaned up export of Zotero with missing DOIs added, author name 
			variants collapsed, and Marijns paper metadata added (long, short, 
			demo, etc).

all-authors.tsv		Tidy subset of all-data.tsv with three columns (DOI, year, author) 					
			with one row per author.

all-codes.tsv		Tidy subset of all-data.tsv with three columns (DOI, year, code) 
			with one row per code. This contains all our original codes 
			without filtering.

filtered-codes.tsv	Filtered version of all-codes.tsv in the same format. This one is 					
			filtered so only codes on my whitelist remain. For instance, since 
			participant counts were not annotated consistently, I do not 						
			include them on my whitelist, so they're filtered out. I have also 
			consolidated some of our codes, such as converting many of our 
			research type codes ('design;type;exploratory', 
			'design;type;predictive', ...) into 'design;type;experimental').

all-data.one-hot.tsv	Same as all-data.tsv but with one-hot encoded columns of all 
			filtered codes.

all-data.one-hot.xlsx	Similar to all-data.one-hot.tsv, but merged with Birgers citation
			analysis spreadsheet.