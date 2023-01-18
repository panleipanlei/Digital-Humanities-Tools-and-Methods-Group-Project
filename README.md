# The Analyse of the Factors that Affect the Stylistic Differences of Colonial South Asian English Literature

## 1. Motivation
Sometimes there are stylistic differences between pieces of literature that are written by authors from a certain period, a certain region, etc. Ted Underwood, Kevin Kiley, Wenyi Shang, and Stephen Vaisey (2022) have found that the birth year of authors explains better than the published year of literature in their corpus of 10,830 works of fiction from 1880 to 1999. One of the assignments we have done this semester shows that the published year is the main factor influencing the stylistic relations between 150 English novels published between 1771 and 1930. We are interested in the situations in other corpus and want to find out the factors there if there are stylistic differences between those pieces of literature.

## 2. Goal of the project
We aim to analyse the factors that affect the stylistic differences of Colonial South Asian English Literature.

## 3. Research question
Are there stylistic differences between authors of different ethnicities writing in English during the time of the British Colonial Empire?

## 4. Dataset
We decide to use the Colonial South Asian Literature corpus from Amardeep Singh’s dataset (2020) which contains books published between 1853 and 1923.
We have made some changes to the dataset. First, the dataset includes 110 pieces of literature in total while the metadata of this corpus only has information on 101 pieces, so we delete those which are not in the metadata. Then we add other possible attributes that may affect the stylistic differences like gender, birth year, and the original language. Finally, South Asia is one of the ethnicities of the authors in the metadata. We change it to Indian and Bangladesh so that it will be more clear when comparing the ethnicities of the authors.

## 5. Tools
### (1) Stylo
First, we will use Stylo to make cluster analyses in the corpus. We may not use the visualizations in the output since the corpus contains 101 pieces of literature. But Stylo will help us get a rough understanding of the stylistic relationship between the literature. One of the outputs of Stylo is the edges file that shows all the relationships - mainly the weight - between the literature.
### (2) Gephi
We will use Gephi to create network visualizations. The edges file from Stylo will be used as input for Gephi. Besides, we will also use a node file with the metadata from Amardeep Singh’s dataset (2020).
Different networks will be plotted when using different attributes for nodes. Some networks might not show stylistic differences if there are no clusters or trends at all. Some may have the main factors while some only show part of the reasons. From these networks, we could find out whether there are stylistic differences between 101 pieces of Colonial South Asian literature, and what affects them most if there are any.
