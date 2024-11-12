# Life-Science-Applications

Here, we will be exploring few healthcare life science applications, and to understand about basics of DNA, RNA and proteins, classifications, major molecule traits and role of AI in healthcare applications.


**Few Basics:**

**1. DNA:** DNA is a set of instructions like a computer program for our human body, Its made up of four nitrogenous bases — adenine (A), thymine (T), cytosine (C), and guanine (G). These bases pair in a specific way: A pairs with T, and C pairs with G.

Gene Count: We as a humans have approximately 19,000-20,000 genes (attached the list), though exact count may vary slightly depending on the source. Genes can be looked up in databases like the one on Wikipedia, which provides an overview of various gene categories and functions.

How to check whether the given sequence is correct DNA or not ?. Valid DNA must contains these four bases: A, T, C and G. Normal python programming functions will be utilized here.


**2. RNA and Transcription:**
Converting DNA to RNA: The process of converting DNA into RNA is called **transcription**. During transcription, an enzyme called RNA polymerase reads the DNA sequence and then creates a complementary RNA strand.

Key Difference (T to U): In RNA, thymine (T) is replaced by uracil (U), so whenever there’s an "A" on the DNA template, it pairs with "U" in the RNA. This switch from "T" to "U" is a unique feature of RNA.

Example:

Our Given DNA Sample Sequence:ATCGTTAG

Converted RNA:AUCGUUAG

We just replaced T with U

This is a basic example, normally the sequence will contain billions of pairs. 

**3. Proteins:**:
convert_into_protein("UUAAUGUUCUUU")

Lets split it into three letters each. 

#UUA - Not a proper starting for protein.
#AUG - It starts with AUG, in short "M"
#UUC - Denotes "F"
#UUU - Denotes "F"

#Final Converted Results as "MFF"

Other Topics:

1. DNA, gene list and its example
2. RNA (concepts and conversion of DNA to RNA with example python scripts)
3. Protein Structure and the list of available open source platforms for further study
4. Similarity Identifications (with python examples)
5. Famous Similarity scores: PAM, BLOSUM Matrices etc. and its open source tools for calculations.
6. Few Classifications/Applications
7. Also, we will train a machine-learning model to predict the activities of new molecules using Auto Variational Encoder and Generative AI applications


Sample Output from Generative AI models (Evaluation with AUC curve, to be verified):
![image](https://github.com/user-attachments/assets/e5e638ca-30db-415e-9dbb-41a155ed70bb)

Below are few project ideas which could be a good start: (Source: GPT4 Generated)

![image](https://github.com/user-attachments/assets/72975c4d-8bb4-485a-877e-9a0c0aedfe31)


**Reference:**
1. https://en.wikipedia.org/wiki/Human_genome
2. https://pypi.org/project/blosum/
3. https://wikidoc.org/index.php/BLOSUM
4. https://deepmind.google/technologies/alphafold/
5. https://blast.ncbi.nlm.nih.gov/Blast.cgi?BLAST_SPEC=blast2seq&LINK_LOC=align2seq&PAGE_TYPE=BlastSearch
6. https://openai.com/ (For content reviews & fact checks)
   
Note: Healthcare is highly regulated field which would require precision and prior experience. These basic concepts/contents has been generated only for educational purpose for life science applications, it's also a good practice to do a fact checks further with the experts in the domain. 

