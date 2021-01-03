
## Automated Decision Making in Society

Decision made by machine learning algorithms are already a part of many aspects
of our lives, although it can sometimes a bit opaque where exactly. For the
writing assignment this week, you'll dive deeper into that question and try to
accertain where algorithms might make decisions in some part of *your* life.
This assignment will be a bit larger than other written assignments, as there
are several articles to read as background and you'll have to do some
investigating yourself.

In 2018 the Dutch ministry of the interior (binnenlandse zaken) did an
exploratory inquery into the use of algorithms by government organisations.
They sent a questionair to other ministeries, provinces and municipalities, the
results of which were analysed by the CBS.
[You can download a PDF with the report here.](https://www.cbs.nl/nl-nl/maatwerk/2018/48/gebruik-van-algoritmen-door-overheidsorganisaties)

Start by reading sections 1 and 2 of the report. Most common among the
respondents is the use of "case-based algorithms" (i.e. machine learning) with
many of the specific algorithms corresponding to methods covered in ML1 and
ML2, including the CNN's from this module. If you're interested in more of the
specifics, part of the questionair responses were made public by a WOB-request
by the NOS and can be searched through
[here](https://app.nos.nl/datavisualisatie/2018/algoritmen/index.html).

In 2018 the EU also introduced the General Data Protection Regulation, which
put into place many regulations regarding the use of (personal) data. The most
important regulations with regards to automated decision making are covered
under Data Subject (that's you) Rights. For a quick overview of what
rights you have under the GDPR, 
[read the summary here.](https://advisera.com/eugdpracademy/knowledgebase/8-data-subject-rights-according-to-gdpr/)

Already in 2016, when the GDPR was still under review, an interesting article
about the potential consequences for machine learning research was published by
Goodman and Flaxman. It gives a good overview of where the privacy regulation
and machine learning reseach potentially clash.
[You can download a PDF with the article here.](https://arxiv.org/pdf/1606.08813)
Read the article before continuing with the rest of the assignment.

As mentioned by Goodman and Flaxman, under article 22 you have the right to
object to *"a decision based solely on automated processing, including
profiling, which produces legal effects concerning [you] or similarly
significantly affects [you]"*. This, of course, requires that you know which
decisions might be based soley on automated processing in the first place. This
right is covered under article 13, which states you should at all times be
provided information on *"the existence of automated decision-making, including
profiling, referred to in article 22 and, at least in those cases, meaningful
information about the logic involved"*. In case you want to dive more
deeply into the details,
[you can find the full text of all the GDPR articles here.](https://gdpr-info.eu/chapter-3/)

What exactly "meaningful information about the logic involved" entails is very
much an active area of debate and has also lead to a big boost of research into
*explainable / interpretable AI* or *FAT ML*. Therefore, answers to questions
regarding the logic involved can in some cases be very hard to provide
currently. For this writing assignment you will try and investigate to what
degree at least questions regarding the existance of automated decision-making
that affects you are actually answerable under the GDPR.

#### Assignment

For this assignment you should pick one private company or government
institution for which you are a *data subject* and which might make automated
decisions that produce *legal effects concerning [you] or similarly
significantly affects [you]*.

The requirements of information that should be available at all times as
described in articles 12, 13 and 14 of the GDPR are usually fulfilled using a
privacy notice or privacy statement provided by the company. These privacy
notices should be easy to find publicly online. Additionally, you can also send
a GDPR access request to the company for any specific information regarding
automated decision making that affects you, as per article 15 of the GDPR. A 
standard template for an article 15 request can be found
[here](https://www.datarequests.org/blog/sample-letter-gdpr-access-request/).
Sending such a request is *not* required for the assignment, as it can take a
while to get a response in some cases, but it might still yield interesting
results.

*Before reading the relevant privacy notice*, answer the following questions:

* **Q1.** What company or institution did you choose?

* **Q2.** Which decisions that affect you do you think this company might make
*soley* automatically? Try to be as complete as possible in your description.

* **Q3.** A decision to, for example, inspect you for fraud can of course be argued
to be only *partially* automatically, if the actual inspection is then done
manually, and therefore need not necessarily be disclosed under the GDPR.
Which decisions you do you think might be made *partially* automatically?
Again, be as complete as possible.

* **Q4.** For one of the potentially automated decisions you listed in Q2 and Q3,
speculate what a machine learning model for that decision might look like. What
kind of training data would it use and what regression/classification
predictions do you think it would make exactly?


Next, read privacy notice and any response you might have gotten from the from
the company you selected, and answer the remaining questions:

* **Q5.** What automated decisions are described by the company? If any automated
decisions are listed, what additional information about the logic involved is
provided?

* **Q6.** Does the answer to Q5 correspond with your expectations from Q2 and Q3?
Where does it differ and what surprised you the most?

* **Q7.** The article by Goodman and Flaxman lists three possible barriers
transparency. Do you think you encountered any of these barriers with your
company? If so, which ones and why?

