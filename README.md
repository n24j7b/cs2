java cAcademic integrity declaration
By submitting work for assessment I hereby declare that I understand the University’s policy on academic
integrity and statement on the use of artificial intelligence software.
In accordance with these documents, I declare that the work submitted is original and solely my work, and that I
have not been assisted by another person (collusion) apart from where the submitted work is for a designated
collaborative task, in which case the individual contributions are indicated. I also declare that I have not used
any editing tools or sources without proper acknowledgment (plagiarism). Where the submitted work is a
computer program or code, I further declare that any copied code is declared in comments identifying the
source at the start of the program or in a header file, that comments inline identify the start and end of the
copied code, and that any modifications to code sources elsewhere are commented upon as to the nature of the
modification.
Unlimited Attempts Allowed
Details
Objective
1. To produce an interactive R Shiny interface to present a dataset of your choice;
2. To use the techniques, principles, and software learned during the subject and lab sessions, including applying
your feedback from Assignment 1;
3. To demonstrate your ability to challenge yourself and innovate in a code-based environment to present data in
an engaging, novel manner.
Learning outcomes
ILO 1. Apply the cognitive and technical principles of information visualisation across various domains
ILO 3. Develop various types of visualisation platforms in order to analyse big data sets
Your task
This is an individual assignment.
You will develop one visually appealing and communicative, interactive data visualisation interface using R
based on a dataset selected by you.
Referring to the R programming and Shiny exercises from Labs 4 to 7, as well as other online resources, you will
need to combine, adapt and build upon these to design and create your own interactive interface containing at
least one form of novel interaction.
Assignment 2: Interactive Data Visualisation in R
2024/9/22
100 Points Possible
In Progress
NEXT UP: Submit Assignment
Attempt 1 Add Comment
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 1/7You will need to get familiar with your chosen dataset and design your interface with reference to the principles of
interaction design, cartography and data graphics learned in the lectures. You will assess your interface according
to these principles and iteratively redesign your interface to improve it.
Your resulting interface must have one or more data visualisations with some form of interaction, although the data
visualisations themselves do not all need to be interactive. The interface must communicate a clear message about
your data to a deﬁﬁned audience, and you must present a one-page design summary explaining your design
decisions that help to achieve this.
Please note, that the focus of this assignment is to create an interface to present the dataset in your chosen
scope and/or geographic area. You are not expected to perform any in-depth data modelling, although data
selection will be an important part of the design process to ensure that only relevant data is available to the user.
What distinguishes this assignment from Assignment 1 is the focus on interface and interactivity and the need to
think more carefully about basic design principles – you can no longer call on Tableau to do some of the thinking
for you.
Ideas
The focus of Assignment 2 is to create an interactive data visualisation interface, NOT analyse a big dataset. That's
why we suggest using pre-packaged data which has already been formatted ready for visualisation. You are free to
choose your own data source or use a dataset from one of the following suggested sources:
Makeover Monday (2018 to present) (https://makeovermonday.co.uk/) Tidy Tuesday (2018 to present)
(https://github.com/rfordatascience/tidytuesday)
Data is Plural (2016 to present) (https://www.data-is-plural.com/)
FiveThirtyEight open data (2014 to 2023) (https://data.ﬁﬁvethirtyeight.com/)
BuzzFeed News (US-centric, 2014 to 2022) (https://github.com/BuzzFeedNews/everything)
Tableau has a blog post about free public data sets (https://www.tableau.com/learn/articles/free-publicdata-sets)
list of places to look for data (https://help.tableau.com/current/pro/desktop/enus/ﬁﬁnd_good_datasets.htm#places-to-look-for-data)
The
 data search engine Kaggle (https://www.kaggle.com/datasets?minUsabilityRating=9.00+or+higher)
IMPORTANT: The following topics are not allowed in 2024 because too many students selected them in
previous years:
Any topics relating to ﬁﬁrearms or homicides in the United States, including gun violence, police
shootings, murders, and so on
Any topics relating to traﬃﬃﬃc accidents in the United States at a state or national scale (city scale is
allowed)
Submissions based on these topics will receive zero marks for Assignment 2. The only exception is if you
wish to incorporate a data graphic on these topics as a minor part of a broader interface. In this case,
please get permission from your tutor.
Technical requirements
You will create an interface in R. You can use any packages you wish; however, you must use Shiny to create an
app (graphical user interface).
In class, we covered ggplot2 (and ggiraph) and some packages for spatial visualisation. Students who are not
familiar with R programming may prefer to explore these libraries more deeply.
If you would like to learn more, there are a number of online books on R and Shiny, for example:
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 2/7Lander, J. P. (2014). R for everyone: Advanced analytics and graphics
(https://cat.lib.unimelb.edu.au:443/record=b7253346~S30) , 2nd edition, Addison-Wesley - introduction to R,
includes a chapter on Shiny
Resnizky, H. (2015). Learning Shiny (https://cat2.lib.unimelb.edu.au/record=b7243085~S30) , O'Reilly - simple
intro to R and Shiny, limited material on data graphics
Chang, W. (2018). R Graphics Cookbook (https://cat.lib.unimelb.edu.au:443/record=b7253353~S30) , 2nd edition,
O'Reilly - focus on ggplot2 graphics
Sievert, C. (2019). Interactive web-based data visualization with R, plotly, and shiny (https://plotly-r.com/)
Your R code should:
contain the library(...) commands necessary to load any packages required by your R code. You may use any
packages from CRAN (https://cran.r-project.org/web/packages/available_packages_by_name.html)
be written with the assumption that the directory containing your R script has been set as the working directory.
For example, read.csv("deaths-1900.csv")
contain a comment above every section of your script to describe what that section does.
Your R code should not:
contain install.packages(...) commands.
contain full ﬁﬁle paths (e.g. "C:/Users/...") or ﬁﬁle.choose() functions.
You will be penalised if the marker has to modify your code to get it working, and heavily penalised if the marker is
unable to get your code working with reasonable eﬀﬀort.
Submission
This exercise is to be completed individually on your own time.
The assessment is worth 20% of your ﬁﬁnal subject mark.
You must submit the following through Canvas:
1. A zipped ﬁﬁle containing any data sets you used and working R code that generates the data graphic with a
clear acknowledgement of any code used or adapted from other sources. There should be no
folders/directories inside the zip ﬁﬁle unless absolutely unavoidable. 
2. A PDF design summary report, submitted simultaneously into Canvas (not inside your zipped ﬁﬁle), containing
the following:
A one-page summary of your design;
An appendix (on a second page if required) that clearly describes all of the sources used in your design and
describes how the sources are used in your interface. [clariﬁﬁcation added 10 September]
In your one-page summary, you can also provide extra information about your design to highlight any background
work or to assist the user in understanding and/or using your interface.
REMEMBER: Please read the important note above about topics that are not allowed. An interface based
on these topics will score zero marks.
Deadline
The submission deadline is Sunday 22 September 2024 at 23:59.
A late penalty may be applied on the basis of the lateness if no extension is approved prior to the deadline.
Students must apply for an extension directly to the Subject Admin, Peyman Jafary, via
jafary.p@unimelb.edu.au (mailto:jafary.p@unimelb.edu.au) .
Assessments submitted after the original due date without an extension, or after the new due date if an
extension has been granted by the Subject Coordinator, will be subject to a penalty of 10% in the mark
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 3/7received in this assessment for each working day the assessment task is late. For example, if you are late
by one day and your assessment reaches a standard of 80 out of 100, you will now receive 70 in this
assessment only.
Assessment Criteria
The key assessment criteria are written below as part of the rubric.
As a guide to grade-related criteria: 
80%: Outstanding work that demonstrates substantial additional technical challenges, substantial design
innovation, ﬂﬂawless design, and involves work that clearly goes beyond that normally expected in class.  
Hints
You are free to design any type of data graphic. You do not need to design an interface that contains spatial
data, although you are most welcome to do so if you wish. High-quality visualisations containing spatial data
will be rewarded in the grade accordingly.
You should aim to design your own data graphic, not simply duplicate an existing one. Copying will be
penalised under any categories and is a form of plagiarism.
You are encouraged to conduct extensive research to ﬁﬁnd interesting and engaging ways of constructing your
data graphic. This might be where most of your time is spent.
Think carefully about your use of visual variables. These have been key discussion points in many lectures. 
Consider the principles of data integrity, aesthetics, correspondence, and density in your design based on what
has been discussed in the lecture.Your summary and interface must be carefully designed. If your interface requires a page of dense text to
explain, it is unlikely that the interface itself is well-designed and intuitive to use. Thus, it is recommended that
you keep the design summary as brief as you can while providing a clear explanation of your interface and the
design decisions involved.
Note that your design summary will be assessed based on its design. You should take care to ensure the
design summary is carefully presented with attention to detail. For example, you may prefer to have an
annotated diagram as your design summary instead of text.
Spelling and grammar are part of the assessment as well. Your design summary and interface should exhibit
attention to detail and be free of errors.
Plagiarism
In short: you must clearly acknowledge any material you have used in your assessment. Plagiarism is
copying, and use of another’s work without proper acknowledgment (can be both known and unknown). The
university has a clear policy prohibiting any form of plagiarism. Further information can be found at
https://academicintegrity.unimelb.edu.au/ (https://academicintegrity.unimelb.edu.au/) .
Note that it is acceptable to reuse ideas and code you have found on the web as long as the source is
acknowledged and that use is permitted by any license restrictions. If properly acknowledged, using other people’s
code and ideas can count as independent background research (see grade-related criteria above). If not properly
acknowledged, using other people’s code and ideas is plagiarism and will result in a mark of zero for this
assessment. In serious cases, plagiarism may also result in failure of the entire subject and further University
disciplinary action. 
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 4/7QA
If you have any questions about Assessment 2, please post them on the Discussion Board
(https://canvas.lms.unimelb.edu.au/courses/188035/discussion_topics/1130374) for this assessment. The tutors will
attend to questions there on a regular basis. If you know the answer to any questions, you are also welcome to
post your answer. You can also ask questions in the lab sessions. We are a learning community and interaction is
always welcome. Of course, if you have any speciﬁﬁc questions, you can also email your tutor to seek help.
View Rubric
GEOM90007 Assignment 2 Rubric
Criteria Ratings Pts
Data
correspondence
25 to >19.8 pts
Outstanding
The interface is
neat, totally
consistent and
crystal-clear to
understand.
There is a
strong, coherent
theme/message
that reveals
interesting and
insightful
patterns in the
data. Highly
tailored to the
audience’s
needs. Overall,
the interface is
virtually
ﬂﬂawless.
19.8 to >17.3
pts
Very Good
The interface is
neat, consistent
and easy to
understand.
There is a
logical
theme/message
that reveals
meaningful
patterns in the
data. Tailored to
the audience’s
needs. Overall,
there are a few
minor issues.
17.3 to >14.8
pts
Good
The interface is
mostly neat,
somewhat
consistent and
mostly easy to
understand.
Some parts
could be clearer.
There is a
theme/message
that reveals
some patterns
in the data.
Overall, there
are several
minor issues or
a few major
issues.
14.8 to >11.1
pts
Flawed
The interface is
not neat and
quite
inconsistent. It
is mostly
confusing and
diﬃﬃﬃcult to
understand. The
theme/message
may be weak or
unclear, with a
limited number
of relevant
patterns
apparent.
Overall, the
interface has
several major
and minor
issues.
11.1 to >0 pts
Inadequate
The interface is
incomprehensible.
It does not
reveal any
relevant
patterns in the
data. There is
no theme or
visual hierarchy
at all; a few
random
visualisations
have been
created.
/ 25 pts
Data integrity
15 to >11.8 pts
Outstanding
No integrity
issues at all.
Visualisation
types are
always
appropriate and
implemented
with care and
accuracy.
11.8 to >10.3
pts
Very Good
No serious
integrity
concerns or
ﬂﬂaws.
Visualisation
types are
appropriate and
implemented
correctly. Some
minor issues.
10.3 to >8.8 pts
Good
Minor data
integrity ﬂﬂaws
exist.
Visualisation
types are
generally
appropriate but
may be
implemented
with some gaps.
8.8 to >6.5 pts
Flawed
Serious data
integrity ﬂﬂaws
exist.
Inappropriate
visualisation
types may be
used. Key
elements may
be frequently
misleading or
absent.
6.5 to >0 pts
Inadequate
There is no
respect for data
integrity. A
critical data
integrity ﬂﬂaw
may exist which
undermines a
major part of
the interface's
message.
/ 15 pts
Data density and
aesthetics
25 to >19.8 pts
Outstanding
The interface’s
look is fresh,
creative,
innovative and
striking, yet
highly eﬀﬀective
and not overly
complex. Well19.8
 to >17.3
pts
Very Good
The dashboard
is aesthetically
pleasing and
demonstrates
developing
creativity and
innovation. Data
17.3 to >14.8
pts
Good
The
dashboard’s
look is eﬀﬀective
with basic
creativity and
innovation. Data
density issues
14.8 to >11.1
pts
Flawed
The dashboard
has aesthetic
ﬂﬂaws. Limited or
ineﬀﬀective
attempts at
creative and
innovative
11.1 to >0 pts
Inadequate
The
dashboard’s
look is
inconsistent and
violates
essential design
principles,
creating a
/ 25 pts
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 5/7GEOM90007 Assignment 2 Rubric
Criteria Ratings Pts
balanced layout;
data density is
neither too high
nor too low.
Attention to
detail is
ﬂﬂawless. Overall
the dashboard
is nearprofessional
quality.
density
 does
not interfere
with the
interface’s
purpose. Some
minor issues
need
improvement
(e.g. the
balance of the
dashboard’s
layout). Minor
issues with
attention to
detail (e.g.
spelling).
occasionally
interfere with
the interface's
purpose. Design
principles are
addressed with
several minor
issues or a few
major issues.
There are gaps
in the attention
to detail.
presentation.
Data density is
too low or too
high; the
available screen
space could be
used more
eﬀﬀectively.
Several major
and minor
issues in design
principles. Low
attention to
detail.
negative
experience for
the audience.
Data density
may be so low
or high that
large parts of
the interface
cannot be
understood.
Technical challenge
and interaction
design
25 to >19.8 pts
Strong
Challenge
Advanced Shiny
features are
used
masterfully,
demonstrating
independent
background
research. The
interaction
design is fully
intuitive and
nearprofessional
quality.
 The
dashboard is an
outstanding
example of
what is possible
with Shiny.
19.8 to >17.3
pts
Developing
Challenge
Advanced Shiny
features are
used eﬀﬀectively.
They adapt to
the needs of the
graphic. The
interaction
design is
appropriate,
intuitive and
high quality.
17.3 to >14.8
pts
Minor
Challenge
Advanced Shiny
features add
some value, but
more eﬀﬀort is
needed to
maximise their
eﬀﬀectiveness.
The interaction
design is often
intuitive but
sometimes
confusing.
14.8 to >11.1
pts
Limited
Challenge
Limited use of
advanced Shiny
features. A few
eﬀﬀorts were
made, but these
eﬀﬀorts are of
limited value to
the dashboard’s
audience. The
interface often
violates the
norms of
interaction
design; major
parts are not
intuitive or
confusing to
use.
11.1 to >0 pts
Poor or No
Challenge
Ineﬀﬀective or no
use of
advanced Shiny
features.
Interacting with
the interface is a
very frustrating
or impossible
experience.
There may be
major bugs.
/ 25 pts
Design summary 10 to >7.8 pts
Outstanding
The design
summary is
well-structured
and strongly
justiﬁﬁes all
design choices.
The student
clearly
understands
concepts from
lectures and is
able to put
these ideas into
practice
eﬀﬀectively. The
layout is
7.8 to >6.8 pts
Very Good
The design
summary is
well-structured
and justiﬁﬁes the
design choices.
The student
shows a good
understanding
of some
concepts from
lectures and
links these to
their design
choices. The
layout is
eﬀﬀective.
6.8 to >5.8 pts
Good
The design
summary
explains some
design choices,
but a few
elements are
missing. Some
basic links are
made between
the lecture
material and the
interface
design. The
structure is
adequate. The
layout is basic
5.8 to >4.3 pts
Flawed
The design
summary has
major ﬂﬂaws. For
instance, it may
be highly
descriptive or
restates the
obvious; it may
belong to the
wrong genre of
writing (e.g.
user tutorial); it
may be too
brief. The
structure needs
improvement.
4.3 to >0 pts
Inadequate
EITHER: The
design
summary
contains little or
no relevant
content at all.
OR: It exceeds
the one-page
limit. OR: No
summary was
submitted at all
(zero marks).
/ 10 pts
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 6/7Choose a submission type.
GEOM90007 Assignment 2 Rubric
Criteria Ratings Pts
creative. The
writing is
crystal-clear.
and mostly
eﬀﬀective.
The layout is
crude or
ineﬀﬀective.
Total Points: 0
Upload More
Choose a ﬁﬁle to upload
File permitted: ZIP, PDF, TXT
 
Canvas Files
I agree to the tool's End-User License Agreement (https://api.turnitin.com/api/lti/1p0/user/static_eula)
This assignment submission is my own, original work
Submit Assignment
or
2024/9/20 10:24 Canvas LMS
https://canvas.lms.unimelb.edu.au/courses/188035/assignments/468024 7/7

         
加QQ：99515681  WX：codinghelp
