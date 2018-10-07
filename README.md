# Genoceanic
Leveraging the power of Open Data Standards in the world of Genomics.
*Author: Dr Shane McKee* shane.mckee@belfasttrust.hscni.net

## What is Genoceanic?
Northern Ireland patients are participating in the UK [**100,000 Genomes Project**](https://www.genomicsengland.co.uk/). This involves collating **consent**, **phenotype** and **genomic** data and transmitting this securely to [*Genomics England Ltd*](https://www.genomicsengland.co.uk/).

We aim to recruit up to 1000 patients and relatives with a variety of rare diseases and cancers to the Northern Ireland contribution to the 100KGP. 

Genoceanic consists of two primary components:

1. A front end for data entry and review, called **GENIE**
1. A clinical data repository based on **OpenEHR**

## What is GENIE?
- GENIE is a software platform created by [University Hospitals Birmingham to support the West Midlands Genomic Medicine Centre](https://www.uhb.nhs.uk/west-midlands-genomic-medicine-centre.htm)'s activity within the 100,000 Genomes Project. 
- set up data formats to match GEL dataset
- synchronise data
- allow recruitment and data management
- align with ordering system for the new Genetic test directory

## What is OpenEHR?
- [OpenEHR](http://www.openehr.org) is the de facto international standard information modelling system for healthcare data.
- Constructing our dataset in OpenEHR will allow linkages with other health and care systems, particularly as we move out of silos towards an [Open Platform Architecture](http://apperta.org/openplatforms).
- The OpenEHR data model is portable between care settings.
- OpenEHR is clinically curated, ensuring it meets the real-world needs of healthcare.
- OpenEHR allows rich data acquisition to inform analysis of genomic data.
- Archetypes and Templates developed on the OpenEHR background can be re-used by other applications and services, providing a platform for innovation across all aspects of healthcare.

## Where will Genoceanic be housed?
Initially Genoceanic will "live" within the Belfast Trust, as the lead organisation for the recruitment of NI patients into the 100KGP. As we gain experience with the platform, the intention is to move several legacy systems onto the 

## How will we connect everything up?
This is going to get a little technical. We actually do have a great deal of data about our health and care in digital systems. The problem is that these systems are typically very bad at talking to each other, and setting up linkages can be a difficult, time-consuming and expensive process. However we plan to significantly simplify this process by using the **Mirth** engine to build linkages between Belfast Trust IT systems and Genoceanic's OpenEHR clinical data repository (CDR). We will then connect the OpenEHR CDR to GeNIE, allowing interchange of data. GeNIE will act as both the user interface by which we access the clinical data for the genomics programme, and the exchange engine for communicating with the Genomics England Ltd databases. This is a very simple but powerful architecture, and means we can get maximum benefit.

As the new National Genomic Medicine Service comes on-line in England, we will use GeNIE as the basis for test ordering for send-away genetic tests to English laboratories. This structure will ensure that the data will follow the samples, allowing better test targeting, considerable improvements in access to genetic testing, and a much smoother and more streamlined process. Performance data for commissioners will also be much easier and faster to collect, allowing decisions to be made in a more timely manner, and commissioned tests to be more comprehensively overseen. 

## Why the name "Genoceanic"?
In the late 19th and early 20th centuries, Belfast was the ship-building capital of the world, with its Harland & Wolff shipyard designing and constructing some of the most iconic liners of the period, including the ill-fated Titanic. **Oceanic** was one of H&W's earlier liners, and at the time of her construction, she was the largest and most versatile ship ever built. 
"Genoceanic" stands for **Gen**omic **O**pen **C**ore **E**ngine for **A**ccelerating **NI** **C**are. Using this architecture, we can ensure that our developments in genomics will align with regional and national objectives to ensure that the clinical data which our patients have entrusted to us will continue to provide benefit when Encompass comes along.

## How does Genoceanic relate to Encompass?
Genoceanic is a separate project from Encompass, but is designed to use open data standards (OpenEHR), so that it can ultimately be integrated with Encompass and/or the vendor-neutral open platform that works along with the Encompass architecture. The philosophy is "Once for Northern Ireland" - Genoceanic will be built to work alongside regional developments, and not in its own little silo. Although the initial phase will be developed within Belfast Trust, our plan is to liaise with regional stakeholders and the Encompass team at the earliest available opportunity after the award of contract to establish the relevant data linkages. We are satisfied that the requirements of Genoceanic are sufficiently generic that they will have no influence over the selection process for Encompass.

So the bottom line is: we *are excited and can't wait* for Encompass! We're preparing the road for the next digital revolution in Northern Ireland's health & care system. We need to be ready to hit the ground running to ensure that digital healthcare and precision medicine have a synergistic effect in improving the health and wellbeing of our patients and the wider population.
