# Dog breed popularity


## Purpose

The purpose of this project is to visualize the popularity of various dog breeds.


## Original source

Data source:  https://figshare.com/articles/dataset/American_Kennel_Club_Breed_Popularity_Statistics/715895

The dataset contains the number of puppies of each breed registered by the [American Kennel Club](https://www.akc.org/) from 1926-2005.


## Cleaning in Excel

### Dachshund

Eliminated XX and XX (long-haired) row where both values matched
1930-1936 combined values into Dachshund row
Removed misspelled, duplicate “Daschund” (sic) lines 1926-1939 (totals didn't always match up exactly)


### Fox Terrier
1926-1936, 1945-1951,1985-     Kept combined row, deleted (Smooth) and (Wire)	 rows
1937-1944,1952-1984        Removed -XX row (same count as Fox Terrier row)
Kept (Toy) rows separately, first in 2002
#### Potential anomalies 
Fox Terrier Smooth and Wire are both 1205 (total 2410) in 2004.  In 2005, both are 1141 (total 2282). Retained for this analysis


### Manchester Terrier
1926-1945 removed XX and Toy rows, kept total row
1946-2005 removed duplicate XX row (1958 removed -XX from row, total row was missing)


### Poodle
1926-1945  removed miniature and toy rows, kept total row (no miniature line for 1939, no toy line 1943-1945)
1946-2005  removed XX line, kept total line


### English Toy Spaniel
Deleted English Toy Spaniel (All) rows.  Duplicates of English Toy Spaniel (Blenheim and Prince Charles lines), there was no All row for 1973


### Spaniel (Cocker)
Kept All Cockers row, deleted American type... and English Cocker rows
