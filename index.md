---
permalink: index.html
site: sandpaper::sandpaper_site
---

Good data organization is the foundation of any research project. It not only sets you up nicely for analysis, 
but it also makes it easier to come back to the project later and share it with collaborators, including
your most crucial collaborator - **future you**.  
  
  
Organizing a project that includes sequencing involves many components. There's the experimental setup 
and conditions metadata, measurements of experimental parameters, sequencing preparation, and sample 
information, the sequences themselves, and the files and workflow of any bioinformatics analysis. 
So much of the information of a sequencing project is digital, and we need to keep track of our 
digital records in the same way we have a lab notebook and sample freezer. This organization makes you a more effective bioinformatics researcher and prepares 
your data and project for publication, as grant agencies and publishers increasingly require this information. In this lesson, we'll go 
through the project organization and documentation that will make an efficient bioinformatics workflow 
possible.
  
    
In this lesson, we'll be using data from a study of experimental evolution using data from [Cuatro Ciénegas Basin](https://elifesciences.org/articles/49816). In this study, there are several types of files:
  
- spreadsheet data from the experiment that tracks the microbiome and its phenotype over time
- spreadsheet data with information on the samples that were sequenced, the names of the samples, 
  how they were prepared, and the sequencing conditions
- the sequence data

Throughout the analysis, we'll also generate files from the steps in the bioinformatics pipeline 
and documentation on the tools and parameters that we used.

In this lesson, you will learn the following:

- How to structure your metadata, tabular data, and information about the experiment. 
- The metadata is the information about the experiment and the samples you're sequencing.
- How to prepare for, understand, organize, and store the sequencing data that comes back from the sequencing center.
- How to access and download publicly available data that may need to be used in your bioinformatics analysis.

## Getting Started

::::::::::::::::::::::::::::::::::::::::: prereqs

This lesson assumes no prior experience with the tools covered in the workshop. 
However, learners are expected to have familiarity with some biological concepts,
such as that each living organism has a genome and what can be obtained from DNA sequencing.
Participants should bring their laptops and plan to participate actively. 

This lesson is part of a workshop that uses data hosted on an Amazon Machine Instance (AMI). Workshop participants will be given 
information on how
to log in to the AMI during the workshop. Learners using these materials for the self-directed study will need to set up their own
AMI. Information on setting up an AMI and accessing the required data is provided on the [Metagenomics Workshop Setup page](https://carpentries-lab.github.io/metagenomics-workshop/setup.html).

:::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

## For Instructors
If you are teaching this lesson in a workshop, please see the
[Instructor notes](https://carpentries-lab.github.io/metagenomics-workshop/guide/index.html).

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

This lesson is the first one of the [Metagenomics Workshop](https://carpentries-lab.github.io/metagenomics-workshop/), comprised of four lessons. 

## Lesson Reference
This page and the three episodes in this lesson are adapted from the lesson [Project Organization and Management for Genomics](https://datacarpentry.org/organization-genomics/).

## Citation

Please cite as:
[![DOI](https://jose.theoj.org/papers/10.21105/jose.00209/status.svg)](https://doi.org/10.21105/jose.00209)

Claudia Zirión Martínez; Diego Garfias Gallegos; Tania Vanessa Arellano Fernández; Aarón Espinosa Jaime; Edder D Bustos Díaz; José Abel Lovaco Flores; Luis Gerardo Tejero Gómez; J Abraham Avelar Rivas; Nelly Sélem (March , 2023) A Data Carpentry- Style Metagenomics Workshop


