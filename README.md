Udated 3/15/2021

I listened to President Trump's state of the union address and it seemed to me he used "I" and "me" more than is common.  So I set out to compare the "I/Me/my" to "We/Us/Our" ratio of all the presidents in our history.  It turned out that Trump's was surprisingly normal.  The two salient observations I made were that 1) Washinton and Grant were prolific with "I/me/my", and 2) halfway through FDR's 12 years in office his ratio of "I/We" dropped drastically and remained far lower than during the first half of his presidency.  I speculate that the double-dip recession of 1937-38 jolted him out of his customary patterns of speech.

Methods:

Python script to develop methods for handling text, word counts, and like that.

Full text of every presidential state of the union address is contained in the folder 'Text'.

The source of these texts is: https://en.wikisource.org/wiki/Portal:State_of_the_Union_Speeches_by_United_States_Presidents

I used that portal to open each address, copy the entire body text, paste that into MS Word, and "Save as" using US-ASCII encoding and the filename convention of 'preslname.year' (e.g; "lincoln.1863").

Washington's first address is named "washington.1789" but was actually delivered on 8 Jan 1790, covering events of 1789.  After that initial address, following addresses were then delivered late in the same year until FDR delivered his first address in January, which has become customary since then.

In addition to the raw text files, there is a "ripped" database of every word used by every president in every address, with a corresponding count showing how often each word was used in each address.  That data in CSV format is contained in the file "sotu.csv", with fields/columns ['president', 'year', 'word', 'count'].
