Udated 3/21/2020

Python script to develop methods for handling text, word counts, and like that.

Full text of every presidential state of the union address is contained in the folder '/Text' using a filename convention of 'prezlname.year' (e.g; "lincoln.1863").

The source of these texts is: https://en.wikisource.org/wiki/Portal:State_of_the_Union_Speeches_by_United_States_Presidents

I used that portal to open each address, copy the entire body text, paste that into MS Word, and "Save as" using US-ASCII encoding and the filename convention above.

Washington's first address is named "washington.1789" but which was actually delivered on 8 Jan 1790, covering events of 1789.  After that initial address, following addresses were then delivered late in the same year until FDR delivered his first address in January, which has become customary since then.

In addition to the raw text files, there is a "ripped" database of every word used by every president in every address, with a corresponding count showing how often each word was used in each address.  This data, in CSV format, is contained in the file "sotu.csv".