# Analog sequencer

## Overview

In the analog sequencer, the volumes that generate CV are lined up, and by switching these sequentially, the pattern of CV is generated. The example here has a structure in which two 8-step sequencers are lined up. If this is run in series, it becomes a 16-step 1-system sequencer. When run in parallel, it becomes an 8-step 2-system sequencer. It can be switched with the parrarel / serial switch. Also, when the One Shot switch is turned on, the sequence is played and stopped only once.

In Parrarel mode, two CVs are output separately from CV Out1 and CV Out2. In Serial mode, the same 16-step system is output from both CV Out1 and CV Out2.

## Resources contained in this directory

--analog_sequencer_sch.pdf, analog_sequencer_sch.png: Schematic image file
--Created with Eagle file, Eagle ver. 5.12. The printed circuit board layout file has not been created.
  --eagle / eagle.epf --project file
  --eagle / analog_sequencer.sch --schematic file

## circuit diagram

! [analog sequencer] (analog_sequencer_sch.png)