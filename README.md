# Mining Social Media For Rare Diseases
This project was conceived during the [Biomedical Linked Annotation Hackathon 6](http://blah6.linkedannotation.org/) on February 4-7 2020 in Tokyo, Japan

We are very grateful for the support on this work.

## Description of the project
This work was originated spontaneously while at the BLAH6. Several participants showed interest and gathered to discuss and hack. 

**Day 1**
* Discussion

**Day 2/3**
* Hack a simple experiment to explore the potential of Twitter data as a source of patient-centric knowledge.

### Simple experiment hacked while at the BLAH6
This work was mostly done by Atsuko Yamaguchi.

* Research question
```
Can Twitter data be used as a source of biomedical information for rare disease diagnosis?
```

* Aim
```
To characterize the “patient journey” for undiagnosed patients that have been finally diagnosed. 
```

* Approach
```
Use the patient information timeline to extract biomedical data and analyse the “patient journey” for undiagnosed patients that have been finally diagnosed. We will focus on two specific rare diseases (Multiple sclerosis variant & Amyotrophic lateral sclerosis). 
```

* Tools
	- We will use the Social Media Mining Toolkit [SMMT](https://github.com/thepanacealab/SMMT) developed at BLAH6 by the Panacea Lab to collect and mine Twitter data. 
	- We will use [HPO](https://hpo.jax.org/) to extract symptoms from Twitter data
	- We will use [Kusuri](https://hlp.ibi.upenn.edu/kusuri/home/) to extract drugs from Twitter data.


### Workflow
**IMPORTANT**: Make sure you have your Twitter API keys to collect Twitter data.

TODO


#### 1. Twitter corpus generation
Criteria used:
- Query keywords to search for users: “I was diagnosed” + “rare disease”. 
- Patient diagnosed during last 5 years.
- Selected 5 patient timelines. 
- Retrieved for SMMT: twitter handlers and start-end dates to download the corpus.


### Results
* We mined 3,776 tweets for the five patients
* We tried to extract tweets:
	* related to symptoms by matching terms in HPO. Only two tweets were extracted (pain 1, dementia 1)
	* related to drug by using Kusuri. Bulk upload failed. Two tweets were manually found (vitamin 2)


## Resources
Resources were developed using the SMMT toolkit

* [Twitter data](https://drive.google.com/file/d/1oH4VBBLp0zQVB5gjyLckuF-DQsoAP2TK/view?usp=sharing)


## Contributors
This work was carried out jointly with Atsuko Yamaguchi and Juan M Banda, and with the unvaluable support, guidance and feedback from Graciela Gonzalez-Hernandez, Diana Sousa, Kota Ninomiya, and Davy Weissenbacher.


## Acknowledgments
To BLAH6 organizers and funding agencies for setting up this event that allowed to brought this idea and explore it.

