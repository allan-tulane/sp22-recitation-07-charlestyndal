# CMPS 2200 Recitation 7
## Answers

**Name:**Charles Tyndal



Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |1340                     |826                |.616
alice29.txt    |1039367                     |676374                |.651
asyoulik.txt    |876253                     |606448                |.692
grammar.lsp    |26047                     |17356                |.665
fields.c    |78050                     |56206                |.72

The Huffman Encoding is consistently smaller than the fixed-length due to it being a better algorithm


- **e.**
  If each character has the same frequency, then the cost for each letter is consistent regardless of the document.Since it will be the same frequency, we can assume that the the cost will be n*log(n) where n is the number of leaves on this balanced tree.

