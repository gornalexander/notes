EDH Bank details https://edh.cern.ch/Document/Personnel/BankDetails/9983667 

Hi Matthew!
Regarding Rebecca's sequence double check. I compared two sequences: Rebecca's one and stitched sequence 
[tt24p42\_unsplit\_savedseq.seq](https://gitlab.cern.ch/acc-models/acc-models-tls/-/blob/main/sps_extraction/tt24p42_unsplit/line/jmad/tt24p42_unsplit_savedseq.seq?ref_type=heads)
 from acc-models. 

(1) There some elements that are present in both sequences, I summarised them in "present_in_both_seq.csv" table. Row name suffixes "_r" and "_s" stand for Rebecca's and stitched model values correspondingly. d<parameter_name> rows stand for the difference <parameter_name>_s -  <parameter_name>_r. 
Although these elements have the same names in the both sequences, some of them have:
- different apertypes
- apertures of elements downstream P42 are not present
- slightly different positions along the beam line

(2) Besides the elements from (1), there are unique elements in both of the sequences. In order to find the elements  that are probably similar, but have different names in the sequences, I made a table "stitched_seq_plus_rebeccas_unique.csv" including full stitched model sequence plus unique elements from Rebecca's one. I also marked them all with one of the keywords "duplicate", "s_unique" or "r_unique" and sorted by the position along the line. I would expect to see some "s_unique" and "r_unique" elements having the same position, but because of the slight longitudinal displacement mentioned in (1), there are only such elements located suspiciously close to each other.

So, we need to do the following steps to make the correct sequence:
1.  Add correct apertures and apertypes for elements in (1) or verify the values from Rebecca's sequence for them.
2.