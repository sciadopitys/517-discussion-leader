# Discussion leader assignment for Comp 417/517

In this assignment you will lead discussions and be
responsible for the following three elements:

1. Fill out paper review form
2. Short presentation highlighting key moves and
   contributions of the paper 
3. Facilitating discussion. 
 
## Review Form (25%)

Fill out and commit by midnight the night before: 

[Standard Review Form](./review.md)

Note for most of these sections, concision is preferred.
Provide 1-2 sentences if possible, of course go over if you
need.

## Presentation (25%)

The goal of leading the presentation is to format your
understanding of the paper from the perspective of a
critical reader. It is more an exercise to capture that
you've extracted the critical elements from the paper, as
well as a quick refresher to the class. 

The following slides are expected:

1. Title Page
2. Problem and Motivation
3. Why isn't it solved?
4. The key hypothesis of this paper?
5. The methods used to achieve it (how)?
6. The evaluation results
7. Key takeaways

The presentation should take between 5-12 minutes.

## Discussion Leading (%25)

Develop 5-7 questions after reviewing the online discussion
and lead an initial 15 minute small group and a larger 15
minute discussion.

## Discussion Debrief (%25)

Answer the following questions: 

1. What new insights came out of the discussion? There is probably a "sweet spot" of increasing scalabity on multiprocessor systems by running more VMs at once and the increasing VM-related overheads caused by running them.  Perhaps this is reached when the # of running VMs equals the # of processors?
2. Was there disagreement? Why? The main point of disagreement was whether or not the fact that OSes may need to be modified in order to run efficiently (with less overheads) on Disco is a problem or not.  Some said that the modifications may not be as slight or easy to implement as the authors suggested.  Others said that they amount and difficulty of these modifications should not be much more than that for porting OSes to different hardware, which is already done quite often.
3. What was the consensus about the work?  The consensus was that the work was effective, and a good alternative to other possible configurations such as simply networking a bunch of single-OS computers together (which seems to have much larger communication overheads than the page-sharing mechanism provided by Disco).
