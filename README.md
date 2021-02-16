# BOVERI-559
Parse indels from all available runs to start testing plan

We have a partial list of called indels from BOVERI-540. However, we need a complete list of called indels with the annotation that includes all available MiSeq v5, MiSeq v5, NextSeq v4, and NextSeq v5 runs. 

We need to parse all the indel calls from the new algorithm in all vt5 NextSeq samples. This will help to select more EGFR exon 19 indels for ddPCR. 

To help with the selection, we need the following annotation: %VAF, coverage,PR score, complexity_penalty, support_penalty, overlap_penalty, confidence. 
