# Meeting_notes
Notes about various meetings that are relevant to lab project

## Physics of behavior
- date: 2020-04-30
- recording of the meeting [here](https://www.youtube.com/watch?v=xSwWAgp2VdU)
- meeting notes [here](https://github.com/wAOndering/Meeting_notes/blob/master/Physics%20of%20behavior.md)


## B-SOiD
- date: 2020-05-12
### VIDEO1 (theory):
https://www.youtube.com/watch?v=tpzuXfzyXhQ&t=18s 
(~min 11 clarification of tSNE analysis process)
(~min 20 importance of looking at trajectory enabled by this type of approach vs bout duration (some of those principles may be relevant in the context of tactile sensitivity)
(~min 25 identification of subaction, this can be relevant in the context of pole touching subaction of behavior that leads to "touch" of the pole vs "no touch" and how those subaction may be different between genotypes)

Key takeaway:
B-SOiD statistical tool (step after DLC) extract natural statistic and relationship overtime
B-SOiD not limited to openfeild very versitile 
The name of cluster action are assigned after the fact

### VIDEO2 (howTo):
https://www.youtube.com/watch?v=wFZFDpUBPjI&t=2959s
They have python and matlab version the recommendation as of 4/29 is to use the Matlab version as the Python version is quite rough regarding tSNE analysis parameters that can be fed in (min 31) also some feature are not implemented in python yet (but are in matlab)
(~ min15 importance about feature selection weight and tSNE)
(~min 43 mention about frame extraction with ffmpeg NOTE FOR FUTURE also see https://medium.com/@haydenfaulkner/extracting-frames-fast-from-a-video-using-opencv-and-python-73b9b7dc9661 and check which one is faster to perform task layering numba gpu processing etc. could be done eventually or something written in C, DLC frame extraction present as well relatively slow)
(~min 48 feature and point selection comment)
(~min 50 limit to 1.10^6 rows <=> to 30 min minutes video at highspeed 500frames/seconds long for computation of the tSNE from 1hr to overnight - TRAINING step)
(~min 63 training data set 18000 frames [at least 10000 frames])
