The file "rocks_mdsN.txt" contains the individual-subject similarity-ratings data for Subject N.
Each file has 465 rows.  Each row corresponds to a single trial in which the subject rated the similarity between two rocks, denoted here i and j.  In 435 of the rows, the similarity rating is between two rocks from different subtypes.   In the remaining 30 rows, the similarity rating is between two rocks from the same subtype.

In each row, the columns are as follows:

Column 1:   subtype # of rock i    [Subtype(i)]
Column 2:   subtype # of rock j    [Subtype(j)]
Column 3:   token # of rock i      [Token(i)]
Column 4:   token # of rock j      [Token(j)]

Column 5:   similarity rating between rocks i and j  [on a scale from 1 (most dissimilar) through 9 (most similar)]



In the numbering system for the 360-rock library, the numbering of rocks i and j is given by:


rock i  =   12*[Subtype(i)-1] + Token(i)
rock j  =   12*[Subtype(j)-1] + Token(j)


The file "xlow_rocks_mdsN.txt" contains the individual-subject similarity-ratings data for Subject N.   The file has the prefix "xlow" because the subject's similarity ratings had a low correlation with the averaged ratings of the group and were excluded from the analyses of the similarity ratings provided in the article.  The format of these data files is the same as for the files "rocks_mdsN.txt".

