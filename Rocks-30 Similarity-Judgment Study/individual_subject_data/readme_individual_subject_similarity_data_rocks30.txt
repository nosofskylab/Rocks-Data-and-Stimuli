The file "rocks_mdsN.txt" contains the individual-subject similarity-ratings data for Subject N.
Each file has 435 rows.  Each row corresponds to a single trial in which the subject rates the similarity between two rocks, denoted here i and j.  Rock i is a representative token of one subype of rock, and rock j is a representative token of the second subtype of rock.   

In each row, the columns are as follows:

Column 1:   subtype # of rock i    [Subtype(i)]
Column 2:   subtype # of rock j    [Subtype(j)]
Column 3:   similarity rating between rocks i and j  [on a scale from 1 (most dissimilar) through 9 (most similar)]

In the 360-rock library, the specific number associated with the token that represents each subtype is provided in the file
"rocknumber_translations.txt", copied here for redundancy:

 1   6 Andesite 6
 2  14 Basalt 2
 3  34 Diorite 10
 4  39 Gabbro 3
 5  59 Granite 11
 6  69 Obsidian 9
 7  73 Pegmatite 1
 8  95 Peridotite 11
 9 102 Pumice 6
10 119 Rhyolite 11

11 127 Amphibolite 7
12 144 Anthracite 12
13 151 Gness 7
14 164 Hornfels 8
15 172 Marble 4
16 188 Migmatite 8
17 201 Phyllite 9
18 213 Quartzite 9
19 218 Schist 2
20 237 Slate 9

21 250 Bituminous Coal 10
22 263 Breccia 11
23 267 Chert 3
24 284 Conglomerate 8
25 300 Dolomite 12
26 309 Micrite 9
27 314 Rock Gypsum 2
28 336 Rock Salt 12
29 348 Sandstone 12
30 352 Shale 4

Each in each row, Column 1 gives the subtype number; Column 2 the specific number of the rock that represented that subtype in the rocks-30 similarity-judgment experiment;  Column 3 the subtype name; and Column 4 the token number of the specific rock within its subtype in the rocks library.


The file "low_rocks_mdsN.txt" contains the individual-subject similarity-ratings data for Subject N.   The file has the prefix "low" because the subject's similarity ratings had a low correlation with the averaged ratings of the group. These data were not included in the analyses of the similarity ratings provided in the article.  The format of these data files is the same as for the files "rocks_mdsN.txt".





   