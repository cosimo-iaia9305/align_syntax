# align_syntax
A toolbox to align syntactic structures to word timestamps

*** Toolbox for aligning syntactic structures to word timestamps. 

Authors: Cosimo Iaia, Alessandro Tavano


*** Data folder description
1) AliceChapterOne-EEG.csv contains the annotations of the first Chapter of Alice in wonderland, available here: https://deepblue.lib.umich.edu/data/concern/data_sets/bn999738r#read_me_display

Reference
Brennan, J. R. (2023). EEG Datasets for Naturalistic Listening to "Alice in Wonderland" (Version 2) [Data set], University of Michigan - Deep Blue Data. https://doi.org/10.7302/746w-g237

License: http://creativecommons.org/licenses/by/4.0/


2) example_fig_timestamps.csv contains the word annotations of the sentence "The idea of one employee improved the quality of the product.

3) example_contracted_english.csv contains the word annotations for the sentence "I hadn't thought that there was too much you didn't like eating yesterday at my parents'."

For file 2) and 3), the annotations are performed using Praat (www.praat.org)




*** Script

4) Annotate_align_alice.ipynb shows how to tabulate syntactic structures, sentence by sentence, and align them to the word timestamps. The dataset used in the script is the one described in 1)

5) Annotate_example_figure.ipynb shows how to tabulate and align to word timestamps the syntactic structure of the sentence in 2)

6) Handling_contracted_forms shows how to deal with contracted forms (as in 3)) when perfomring the alignment.




