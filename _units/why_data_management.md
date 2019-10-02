---
layout: page   # This is required
title: Why Learn Data Management?   # This is required

order: 10    # Determines the order of units. Doesn't need to be consecutive though
            # or even start with zero, the pages will be displayed in their sort
            # order.

duration: 10 # A hint to how long it will take to cover this topic in mintues.

tutorial: true  # Set to true if you want this page displayed as a web page
instructors_notes: true  # Set to true if you want this displayed in instructors notes

# Provide a brief description of what the unit is about. You can use markdown
# notation for this.
description: |
  The approach this tutorial takes towards data management is goal oriented in that
  we focus on techniques and tools that promote efficient, open and reproducible science.
  That being said, the process is integral to the goal. We also recognize that the 
  field of software development, especially open source software, is very similar
  to managing research and we therefore borrow considerably from tools and best practices
  that have evolved in that field over the last ten years.

instructors_note: |
  In this part perhaps share stories of bad and good things happening during
  research projects. The goal is to show that these things make you 
  more efficient, make your data easier to understand both for you and others,
  and make it more open and increase impact.
  

  
# These should resolve to files in the supporting_files directory
# or if you specified a different one in _config.yml use that.
# The link_text can be anything you want.
# supporting_files:
#   - file:
#     file_name: first_example_file.txt
#     link_text: Example file  for this unit.
#   - file:
#     file_name: another_example_file.png
#     link_text: Example image for this unit.

---

Researchers have been doing data driven science and scholarship for as long as research has existed. Early astronomers recorded their
observations in notebooks, or even on stone. Mendel's experiments are an early example of modern data driven science. The amount of data
that could be handled was limited by what could be written and read, not to mention the ability to do computations of the data was very 
limited. 

Since the advent of digital computers, their extremely rapid increase in their computational power, the advent of the internet, cheaper and 
cheaper storage and other advancements, the amount of data and other digital artifacts created by researchers and scholars has grown rapidly. 
The concepts of sharing data, validatability and reproducibility have also become increasingly important to both researchers, funders and other
stake holders. At the same time, many funders are starting to require that data be made open and available to others.


## Bigger, Faster and More Complex

The definition of big data typically refers to three attributes. The size of the data is larger than 
can be handled by the traditional tools. The speed with which the data is created or ingested is faster
than can be handled easily. The complexity of the data is greater than can be accomodated. This definition is 
relative, in the sense that with the correct tools and techniques, big data can be turned into "ordinary data".

However, most researchers are not experts in the technologies and skills needed to handle this big data landscape. As 
a result many researchers are finding themselves spending more and more time focused on data management rather than 
their research. These activities don't just include analyzing the data, but also trying to share data with their collaborators 
and others, documenting or explaining their data to their collaborators or others, fixing problems with their data, 
or trying to recover lost or uninterpretable data.

## Efficiency

Perhaps the most immediate benefit that improved data management brings to researchers is efficiency. Spendng 
less time wrangling data, correcting mistakes, discussion what data means and other tasks that can be avoided
the more time researchers can spend working directly on their research.

## Validatation and Reproducibility

These two concepts are related. Research is only valuable to our understanding of the world if you can
validate the results (i.e. the data and analyses can be determined to be correct and appropriate) and the results
can be reproducible. Reproducibility itself can be interepreted in mulitple ways. For our purposes, it refers to the 
ability to rerun the analyses with the data and get the same results. The data and analyses codes must be accessable and 
working for this to happen. A more university reproducibility is conducting the same or similar studies and coming to the 
same conclusions. This is usually beyond the scope of data management.

## Sharing

Research is highly collaborative process in many fields as demonstrated by the increasing number of authors per publication.
If you are collaborating then you are sharing data during a project with your collaborators. This can present many difficulties,
and these difficulties compounded if your collaborators are geographically distributed. Making sure that everyone
understands the data being created or gathered, has access to it and can use it can be diffcult and fraught with difficulty and
errors.

Making data open to the general community is also increasingly common. Some of the same difficulties noted above apply here.
Decisions of how to license the data and preserve and archive it are also important and often new concepts to researchers.

## Data Entropy

An over-arching process common to all the themes touched on so far is **Data Entropy**. This refers to the concept that,
over time, data is constantly lost do to variety of reasons (Figure 1.)

<figure>
  <img src="/assets/img/slides/data_entropy.png" alt="data entropy" style="width:75%%">
  <figcaption>Figure1 - A conceptual diagram of the loss of data over time. (From Michener et al. 1997)</figcaption>
</figure>

As can be seen from the diagram, the loss of data begins immediately. In fact, it probably starts before the time of 
publicaton and from experience, starts from the time of data creation. In practice as data is created, details about 
its creation, formats and other specifics can be quickly forgotten. Over time, memories continue to fade, personell 
move on from the project along with their knowledge that hasn't been recorded. Additonal risks include data loss and
corruption. These can range from loss of entire projects, to losing or deleting individual files, and accidentally changing
names of files or contents of files. 

Better data management can help alleviate all these problems. While there are no one size fits all solutons, by being aware of the
problems and best practices one can adapt the information and tools to fit their own needs. In fact, as with many things,
managing data is an on-going learning process. As new ideas come forth and technologies change, our practices will 
adapt with it. 









