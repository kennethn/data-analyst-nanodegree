# PISA Data
## by Ken Norton

## Dataset

Programme for International Student Assessment (PISA) is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy. The survey was sponsored by Organisation for Economic Co-operation and Development (OECD). Here's a [technical report (PDF)](PISA-2012-technical-report-final.pdf) about the survey and methodology.

**Important Note:** The full dataset (pisa2012.csv) is not included in this repo because it is more than 2.7GB. If you'd like to reproduce my results, you can download a ZIP version of the CSV [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1558738943385000). Just place the unzipped file in the `data` subdirectory.

I analyze the data against Freedom House's [_Freedom in the World_ report](https://en.wikipedia.org/wiki/Freedom_in_the_World#cite_note-FITW-2012-11). I obtained data for all years from [here](https://freedomhouse.org/content/freedom-world-data-and-resources) and then extracted the data for 2012, the same year as the PISA study.

* `political_rights` stands for Political Rights, `civil_liberties` stands for Civil Liberties, and `freedom_status` refers to the Freedom Status.
* `political_rights` and `civil_liberties` are measured on a one-to-seven scale, with one representing the highest degree of Freedom and seven the lowest.
* F, PF, and NF stand for Free, Partly Free, and Not Free.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
