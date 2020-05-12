# samples-mrec
Samples of stereotyped behaviors typical of autism from 6 non-autist participants.

The directories are organized as follows:
  + ParticipantN
      + stereotyped_behavior-activation-level
          - joint<sub>1</sub>;
          ...
          - joint<sub>Z</sub>

> There are 6 participantes (N=6).  
> The stereotyped considered are: body rocking (br), hand flapping (hf), and top spinning (ts).
> The activation level considered are: high (h) and low (l). 
> Each joint has 70 samples (Z=70).

<b>Data file format</b>

tsp, O<sub>1</sub>, O<sub>2</sub>, O<sub>3</sub>, O<sub>4</sub>, x, y, z

where tsp is timestamp, O<sub>1</sub>, ..., O<sub>4</sub> are the orientation of a joint at quaternion notation, and x, y, z are the coordinates of a joint.
