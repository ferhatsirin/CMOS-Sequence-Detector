# CMOS-Sequence-Detector
0.25 u cmos technology

Sequence detector is designed and its CMOS layout is drawed using Magic layout tool.
When detector receives a sequence 1011, its output will be high at the end of the
sequence. For any other sequence, output will be low. Circuit is non-overlapping thus,
an overlapping sequence like 1011011 will output low at the end of sequence, but since
first part of the sequence 1011, it will make output high at that position. Circuit is
designed as a Moore machine, so it will change its output, only if its state is changed.
Input does not affect the output directly.
