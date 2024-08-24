# toronto-star-bestsellers

## Methodology
Data for this project came from the Toronto Star's annual year-end bestseller lists, via the Toronto Public Library, for the years 2000-2023.

The Star's lists had four categories: rank, title, author and publisher. The authors' nationality, gender, race and Indigenous identity, collected was added using self-identification in author biographies on personal/publisher websites and social media pages.

Book cover images were added to the spreadsheet from the Google Books API, which was queried using Python. The spreadsheet can be found in the "static" folder. 

The bookshelf and its moving parts were then made using HTML, JavaScript, CSS (Bootstrap), and a bit more Python. These elements can be found in the "index.html" file. 

Between 2000 and 2014, the Star's bestseller lists were simply separated into fiction and non-fiction. From 2015 onward, fiction and non-fiction by Canadian authors had its own separate section in the year-end list. (Before 2015, Canadian books are found by using the authors' nationality that was added to the data) As a result, the number of books on each shelf will vary until 2015. On sparse shelves (e.g. 2007), readers can see international authors were more prominent those years, with Canadians taking up less space on the bookshelf.

Some years, you will notice multiple appearances by the same books (e.g. 2017). The data includes reprints to give readers additional context for books that reappear on lists over time. As a result, you may see popular titles represented twice in a single year; this is not an error.

The feature article page was created using HTML and CSS's Bootstrap framework for styling. The book stack bar charts and line graphs were created using Canva. The feature article can be found in the "feature_article.html" file.

Like bestseller lists, this project is far from perfect. If you notice any issues with the data or information presented here, you can email me at scottle@cardiff.ac.uk.

## About the Author
Lauren Scott is a settler Canadian journalist currently pursuing a Master's of Computational and Data Journalism (MSc.) at Cardiff University in Cardiff, Wales, U.K.
