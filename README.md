# Life-Science-Applications

Here, we will be exploring few healthcare life science applications, and to understand about basics of human gene, DNA, RNA and proteins, classifications, major diseases traits and role of AI in healthcare applications.

Every human diseases will show certain traits. And, here we will be picking few major diseases which is causing severe impact in human kind and the possibility of leveraging AI in those areas. 


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


**Reference:**
1. https://en.wikipedia.org/wiki/Human_genome
2. https://pypi.org/project/blosum/
3. https://wikidoc.org/index.php/BLOSUM
4. https://deepmind.google/technologies/alphafold/
5. https://blast.ncbi.nlm.nih.gov/Blast.cgi?BLAST_SPEC=blast2seq&LINK_LOC=align2seq&PAGE_TYPE=BlastSearch
