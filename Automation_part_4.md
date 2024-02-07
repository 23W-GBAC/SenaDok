# The fourth part

In the end, I decided that my automation will be about making a table with everythign to be able to organize how everything looks
| City              |  Hospital Name        | Location (On GoogleMaps)     | Website                        |
|-------------------|---------------------------|----------------------|--------------------------------|
| Augsburg | Universitätsklinikum Augsburg - Medizincampus  | https://maps.app.goo.gl/dGMy3igX817tDijx7   | http://www.uk-augsburg.de/ |
| Augsburg | Orthopädische Fachkliniken der Hessing Stiftung | https://maps.app.goo.gl/SKbA9ZLacSdGxc3c6  | http://www.hessing-kliniken.de/ |
| Augsburg | KJF Klinik gGmbH | https://maps.app.goo.gl/fMYVTn7k4mFpHUzT8 | http://www.josefinum.de/ |
| Augsburg | Klinik Vincentinum GmbH & Co. KG | https://maps.app.goo.gl/GdWCxnLJJj7y5Guz7 | http://www.klinik-vincentinum.de/ |
| Augsburg |  Die stadtklinik im diako  | https://maps.app.goo.gl/93RrGLt35tz1fxKD6 | https://stadtklinik-diako.de/ |

Even if I cant add images to my table, it does help make the whole list look better together

I will explain how I made this table:

- Pipe | Symbol:

Separate columns in each row using the pipe symbol (|). This symbol is used to show the boundaries between columns.

- Header Row:

The first row contains the headers of the table. It helps identify the content of each column. I can change the placement of the text within the columns by using colons (:). 

For example, :--- for left-aligned, ---: for right-aligned, and :---: for center-aligned.

- Data Rows:

Sub rows contain data for each hospitals like their name, location, and website. Ensure that the number of columns in each row matches the number of columns in the header so the code works.

- Linking Websites:

I can link a website with using the Markdown link syntax. 
For example, [uk-augsburg.de](http://www.uk-augsburg.de/) creates a hyperlink to Universitätsklinikum Augsburg - Medizincampus Hospital.

- Markdown Preview:

When I add this code to my GitHub Markdown file and commit the changes, GitHub renders the Markdown into a table in the repository.

-----------------

With this code I did also manually have to input every data, which is what I would rather find an automatic way to do it as it takes a long time and automation is for sparing more time. However, it did make my data come all together and make it look more organized and appealing to the eye.
