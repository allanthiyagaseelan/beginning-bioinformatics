# AI Use Log
- Tool/model & version: Gemini and Claude (Sonet 5)
- What I asked for:
1.Used Gemini in tasks P3.1 and P4.1 as directed by the colab notebook.
2.Task 18.1 to understand how fasta file of hominid sequences are created; claude was used.
3.In Rosalind #5, used claude to understand what the pseudocode means to help solve errors in my code.
4.In Rosalind Problem #9 (Computing GC Content) using Biopython's SeqIO.parse() and SeqUtils.gc_fraction() using the pseudocode outline given
Verifying outputs

- Snippet of prompt(s):
1. Pseudocode for Rosalind #9
  Initiate a variable that will be the maximum value of GC content
  In a loop that evaluates each record one at a time:...
--Help me understand this pseudocode and explain what gc function is.
2. Rosalind_6404 0.5375 Rosalind_5959 0.5357142857142857 Rosalind_0808 0.6091954022988506--is this output correct
3. What does the delimited followed by join() do?
4. Examples of all file operations


- What I changed before committing:
1.Changed the names of filenames for certain questions based on the downloaded dataset.
2.AI gave the code in patterns that did not match the hints in the doc. In Rosalind #4, the join() approach and for loop aproach was changed before commit.

- How I verified correctness (tests, sample data):
-Verified the output from Rosalind sample outputs by checking with those parameters in my code.
-Ran the sample data in the code by storing them as text files and used them in colab.


