Udated 3/6/2020

Python script to develop methods for handling text, word counts, and like that.

I am taking two approaches on this.  The first is 'function words' counting, and the second is text sentiment analysis using the Azure Text Analysis service (REST API).

A couple weeks into this project I am grappling with data structures issues.  Sound database design encourages atomic data per column, so I've initially structured the State of the Union raw text dump with four fields: 'president', 'year', 'word', 'count'. But in reshaping the data I'm finding it beneficial to concatenate 'president' and 'year' into a composite field.  So I'm considering an intentional denormalization when forming the DataFrame.

We'll see.