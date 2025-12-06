# rosalind_solutions
Rosalind solutions for GENE5120 (Bioinformatics) Homework 4

1. DNA : "Counting DNA Nucleotides"
This function counts how many of each nucleotide is in a DNA sequence. The sequence is inputted as a string and the output is a count for each nucleotide: A, T, C, and G.

2. RNA : "Transcribing DNA into RNA"
This function transcribes DNA into RNA by replacing all T's with U's. The input is a DNA string, the output is an RNA string.

3. REVC : "Reverse Complement of a DNA Strand"
This function takes a DNA sequence (string) and returns the reverse complement sequence (string)

4. GC : "Computing GC Content"
This code is made up of two functions. The first function determines the percentage of GC conent in each sequence of a dictionary. The second function determines which of these sequences has the highest percentage.
The input is a dictionary of sequences, the output is a sequence ID of the sequence with highest GC content.

5. HAMM : "Counting Point Mutations"
This function determines how many mismatches aka point mutations there are in two dna sequences. Input is 2 dna sequences as string and output is the point mutation count.

6. PROT : "Translating RNA into Protein"
This function takes an RNA sequence, separates it into codons and finds the corresponding amino acids from a dictionary. The input is a RNA sequence as a string and the output is a string of amino acids abbreviations. 

7. SUBS : "Finding a Motif in DNA"
This function searches a string of DNA for a motif. The input is the DNA sequence (string) and motif (substring). The output are the indices of the string in which every instance of the substring is found. 

8. PRTM : "Calculating Protein Mass"
This function searches a dictionary of amino acid masses and adds up the masses of all amino acids found in a protein to calculate protein mass. The input is a string of an amino acid sequence (protein) and the output is the protein mass.

9. REVP: "Finding Reverse Palindromes"
This function finds sequences between 4 and 12 nucleotides that are palindromes, meaning the reverse complement is the same as the forward sequence. The input is a DNA string and the output is the position and length of every reverse palindrome with lengeth 4-12 nucleotides.

10. TRANS : "Calculating Transition/Transversion Ratio"
This function compares two strings and returns the ratio of transitions to transversions. If a base in each position is the same it continues, if they are different but are both purines or both pyrimidines it is counted as a transitions, and if they are different and change from purine to pyrimidine or pyrimidine into purine, it is counted as a transversions. The input are two dna strings and the output is the ratio of transitions to transversions.

   
