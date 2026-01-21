---
title: "Digital Scholar Lab - Collections"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Digital Scholar Lab - Collections

[Return to the main Gale Digital Scholar Lab tutorial](https://mdl.library.utoronto.ca/technology/tutorials/digital-humanities-tools-digital-scholar-lab)

This tutorial shows you how to create a collection in the Digital Scholar Lab, both by searching Gale Primary Sources and by uploading your own texts.

Please note that Gale is periodically adding new documents to their collections, so your document counts and results may look slightly different from our screenshots and examples below.

Table of Contents
-----------------

* [Build a collection](#collection)
* [Upload your own texts](#upload)
	+ [Create a text document](#upload_text_doc)
	+ [Bulk upload, method 1: text files](#upload_bulk1)
	+ [Bulk upload, method 2: spreadsheet (CSV)](#upload_bulk2)

Build a Collection
------------------

([back to table of contents](#table of contents))

The DSL has access to[Gale's extensive digital collections](https://www.gale.com/primary-sources)of newspapers, books, and other archival material. In this tutorial, we will focus on texts by and about an early twentieth\-century scholar named[Sir Aurel Stein](https://en.wikipedia.org/wiki/Aurel_Stein), who travelled throughout South and Central Asia and China as an agent of the British Empire. There are many materials related to him \- works by him, newspaper articles about his expeditions, etc. \- available in the DSL, mostly ranging from the 1920s to the 1940 from a variety of newspapers (*The* *London Times*,*Illustrated London News*,*The Daily Mail*,*The New York Times*) and other digitised holdings from libraries and archives (the British Library, the Smithsonian, the American Antiquarian Society, the National Library of China).

1. When you’re logged in ([instructions for logging in](https://mdl.library.utoronto.ca/technology/tutorials/logging-digital-scholar-lab-through-catalog)), you will need to create your corpus (the collection of texts on which you will run statistics on and create visualizations). To access the search bar, click on **Build** in the top\-right navigation bar.<img src='{{ '/assets/images/DSL_Collections_Build_001.1.jpg' | relative_url }}' alt='Digital Scholar Lab main page with ‘Build’ in the navigation bar highlighted.' title='' width='800' height='578' />

    Although you can use the search bar on the left of the page to get started with a basic search, let’s use the advanced search for a little more precision.**Click on View all limiters in Advanced Search under the search bar.** 
        <img src='{{ '/assets/images/DSL_Collections_Build_001.2.png' | relative_url }}' alt='The Build page with ‘View all limiters in Advanced Search’ highlighted under the main search bar.' title='' width='800' height='480' />
2. You will arrive at the Advanced Search page.  
<img src='{{ '/assets/images/DSL_Collections_Build_002.png' | relative_url }}' alt='Advanced Search page.' title='' width='800' height='512' />

    It is structured like a library catalogue search page. You can use Boolean operators like AND, OR, and NOT to create complex search queries. Gale also automatically suggests[metadata](https://en.wikipedia.org/wiki/Metadata)(e.g. authorship, publication date, language) from their collection as you type.
3. The build page is the first screen where you can view DSL's learning videos. Feel free to watch these as you complete these steps to get an introduction to the features available on that page.  
<img src='{{ '/assets/images/DSL_Collections_Build_003.jpg' | relative_url }}' alt='The build page with the tutorial video highlighted.' title='' width='800' height='499' />
4. Let’s search for Aurel Stein as an Author.**Begin by clicking on the dropdown menu on the right of the first field.** 
<img src='{{ '/assets/images/DSL_Collections_Build_004.png' | relative_url }}' alt='Advanced Search page with the Field drop-down menu highlighted.' title='' width='800' height='264' />
5. **Change it from Keyword to Author.** 
<img src='{{ '/assets/images/DSL_Collections_Build_005.png' | relative_url }}' alt='Advanced Search page with the Field drop-down menu open and Author highlighted.' title='' width='800' height='324' />
6. **Then, click in the search bar and type Aurel Stein.**

    Once you start typing his name, if you have “Author” selected as the search field, you will see at least four different variations of his name appear.

 **Select the first option, “Aurel Stein K. C. I. E.”.** 
        <img src='{{ '/assets/images/DSL_Collections_Build_006.png' | relative_url }}' alt='Advanced Search page with the Terms being filled in.' title='' width='800' height='383' />

    *Note: DSL automatically suggests metadata like author names from its collections, but only if the correct field (e.g. author, keyword) is selected first. Because different databases have input Stein's name differently, there are four variations of his name and thus four different "authors" when searching. Although this is not ideal, it is common when working with data aggregated from many places. Let’s say that we want everything written by Stein, regardless of how his name appears in the various databases.*
7. Because are four variations of his name and we want texts that are attributed to any of them, we will use an OR operator.**Click on the left dropdown menu and select OR.** 
<img src='{{ '/assets/images/DSL_Collections_Build_007.png' | relative_url }}' alt='Advanced Search page with the search row operation set to OR.' title='' width='800' height='260' />

 **Then, repeat the above steps, first changing Keyword to Author, then typing Aurel Stein, and selecting the next variation on his name.**
8. Since there are four variations of his name, we need more than three search terms.**Click on Add a Row at the bottom to add a fourth row.** 
<img src='{{ '/assets/images/DSL_Collections_Build_008.png' | relative_url }}' alt='Advanced Search page with the ‘Add a Row’ button highlighted.' title='' width='800' height='324' />
9. Once you are done, there should be four lines joined with OR.**Click Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_009.png' | relative_url }}' alt='Advanced Search with the ‘Search’ button highlighted.' title='' width='800' height='322' />
10. You now see the search results page.  
<img src='{{ '/assets/images/DSL_Collections_Build_010.png' | relative_url }}' alt='Search result page.' title='' width='800' height='543' />
11. For each result, you will see its title, its author, its OCR Confidence Percentage (see the note below), and a preview of the text.  
<img src='{{ '/assets/images/DSL_Collections_Build_011.png' | relative_url }}' alt='The first search result, its author, OCR rating, ad sample text highlighted.' title='' width='800' height='543' />
12. Additionally, there is some metadata to the right, including the year of publication and the archive, source, and type of the text.  
<img src='{{ '/assets/images/DSL_Collections_Build_012.png' | relative_url }}' alt='The first search result’s publication and document information for highlighted. ' title='' width='800' height='543' />

    *Note: OCR refers to*[*Optical Character Recognition*](https://en.wikipedia.org/wiki/Optical_character_recognition)*. It is a process whereby a program attempts to produce machine\-readable text from a scanned document. The OCR Confidence percentage is an overall score that represents Gale’s confidence in the OCR quality of a specific text.*

    *One factor in their confidence level is the specific OCR algorithm used, since newer OCR algorithms typically perform more accurately than older ones. According to their documentation, over the nearly 20 years Gale has been collecting and scanning documents they have used a variety of OCR algorithms. Gale DSL currently uses Adobe Acrobat with ABBYY5 to OCR scanned documents.*

    *The OCR Confidence percentage additionally relies on other factors, such as the condition of the original document, the quality of the scan, what kind of text is featured in the document, and whether or not there are images in a document.*

    *A caution: the confidence level is useful but not perfect, as some documents can have a lower confidence than they deserve (if they feature lots of images), and some documents with high confidence can still include OCR mistakes. In other words, the confidence percentage is not a replacement for human attention. Some of the oldest scans won’t have a confidence percentage at all, since they predate that system.*
13. Let’s use all of these texts.**Click Select All.** 
<img src='{{ '/assets/images/Collections-13.jpg' | relative_url }}' alt='Search result page, with the ‘Select All’ selection box checked.' title='' width='800' height='484' />
14. **Then click Add to Content Set on the top\-right corner.** 
<img src='{{ '/assets/images/DSL_Collections_Build_014.png' | relative_url }}' alt='In the search menu bar, ‘Add to Content Set’ highlighted. ' title='' width='800' height='543' />
15. **Select New Content Set.** 
<img src='{{ '/assets/images/DSL_Collections_Build_015.1.png' | relative_url }}' alt='Add to Content Set drop down menu with ‘+New content set’ highlighted.' title='' width='500' height='142' />
16. **Name it Stein and click Create. Close the notification that follows.**<img src='{{ '/assets/images/DSL_Collections_Build_016.png' | relative_url }}' alt='New Content Set window with ‘Stein’ written in the name field and the ‘Create’ button highlighted.' title='' width='500' height='215' />
17. Now, let's add some additional texts to this corpus.**On the main toolbar, click on Build.** 
<img src='{{ '/assets/images/DSL_Collections_Build_017.jpg' | relative_url }}' alt='Stein Content set page with ‘Build’ in the navigation bar highlighted.' title='' width='800' height='452' />
18. **Then, click on Advanced Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_018.png' | relative_url }}' alt='The Build page with ‘View all limiters in Advanced Search’ highlighted under the main search bar.' title='' width='800' height='468' />
19. The first time you used Advanced Search, you found texts**by**Aurel Stein. Now, let's look for texts**about**him, by searching for his name in the Keyword.**Just like with steps 3\-7 above, type Aurel Stein into the search bar with Keyword selected this time, select one of the variations that occurs, and repeat with the next line.** 
<img src='{{ '/assets/images/DSL_Collections_Build_019.png' | relative_url }}' alt='Advanced Search page with the Terms being filled in and Field as keyword.' title='' width='800' height='392' />
20. **Like before, choose the three variations of his name. Be sure to use OR to separate all rows. And click on Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_020.png' | relative_url }}' alt='Advanced Search page with the search row operation set to OR and the ‘Search’ button highlighted.' title='' width='800' height='264' />
21. Now there are many more texts. The right sidebar menu offers ways of filtering this dataset. Just to keep our English\-focused analysis consistent, Click on**Languages.** 
<img src='{{ '/assets/images/DSL_Collections_Build_021.1.png' | relative_url }}' alt='Search results page with the Languages filter highlighted.' title='' width='800' height='469' />

    Then **Click on English**, then **click Apply.**<img src='{{ '/assets/images/DSL_Collections_Build_021.2.png' | relative_url }}' alt='Search results page with the Languages filter open and the English selection box checked and highlighted.' title='' width='800' height='486' />
22. Let's add the remaining documents to our collection.**Scroll to the top of the page, click Select All. Then, click Select All (310\) Results.**Remember, your document count may be different. <img src='{{ '/assets/images/DSL_Collections_Build_022.png' | relative_url }}' alt='Search result page, with the ‘Select All’ selection box checked and highlighted. ‘Select All Results’ also highlighted.' title='' width='800' height='528' />
23. **Add this to the content set you just created.** 
<img src='{{ '/assets/images/DSL_Collections_Build_023.png' | relative_url }}' alt='Add to Content Set drop down menu with ‘Stein’ highlighted.' title='' width='500' height='197' />
24. DSL automatically avoids adding duplicates to Content Sets. In this case the notification says that 293 (of 300\) documents were added. Again, your number may be different.**Click Close.** 
<img src='{{ '/assets/images/DSL_Collections_Build_024.jpg' | relative_url }}' alt='Updated Content Set window with the ‘Close’ button highlighted.' title='' width='400' height='177' />
25. To view more information on a specific item, click it, and you will be taken to the Doc Explorer view.**Click the second item, "Sir Aurel Stein and Central Asia."** 
<img src='{{ '/assets/images/DSL_Collections_Build_025.png' | relative_url }}' alt='Search result page, with the title of one of the documents highlighted.' title='' width='800' height='659' />
26. You’ll see the document in its original context on the left, with the text highlighted and the keywords selected. You’ll also get the complete text file on the right. Under image properties, there are options to adjust brightness, contrast, and invert colours, and more.  
<img src='{{ '/assets/images/DSL_Collections_Build_026.jpg' | relative_url }}' alt='The Doc Explorer for the document selected.' title='' width='800' height='585' />
27. By scrolling down, you can see the scanned text on the left, with its text highlighted in light blue, and the specific keywords ("Aurel Stein") highlighted in green.  
<img src='{{ '/assets/images/DSL_Collections_Build_027.png' | relative_url }}' alt='Original document with highlighted name.' title='' width='800' height='900' />
28. Above, you have options to cite, download, email, and print the text. On the left you can open tabs for Explore, Table of Contents, and View Full Citation.  
<img src='{{ '/assets/images/DSL_Collections_Build_028.1.jpg' | relative_url }}' alt='Doc Explorer.  Above the option to ‘Cite’, ‘Send to’, ‘Download’, and ‘Print’ are highlighted. To the left the options to ‘Explore’, ‘Table of Contents’, and ‘View Full Citation” are highlighted. ' title='' width='800' height='585' />

    If you**click on “Learn how this text was created,”**you’ll receive basic information on Gale’s OCR process, and a link to further documentation.  
        <img src='{{ '/assets/images/DSL_Collections_Build_028.2.png' | relative_url }}' alt='Link for ‘Lean how this text was created’ highlighted.' title='' width='800' height='223' />
29. Let’s take a look at our collection.**Click on My Content Sets.** 
<img src='{{ '/assets/images/DSL_Collections_Build_029.1.jpg' | relative_url }}' alt='‘My Content Sets’ in the navigation bar highlighted.' title='' width='600' height='376' />

 **Then click on Stein.**You’ll get an overview of where the texts in this corpus come from.  
        <img src='{{ '/assets/images/DSL_Collections_Build_029.2.jpg' | relative_url }}' alt='My Content Sets Page, with the Stein Content Set highlighted.' title='' width='800' height='418' />
30. To return to the list of texts,**click on the Documents button.** 
<img src='{{ '/assets/images/DSL_Collections_Build_030.jpg' | relative_url }}' alt='The Stein Content Set.' title='' width='800' height='491' />

    By clicking on Documents, you can view and manage the collection, removing texts if you wish. Having a collection means that you don’t need to rerun searches every time you log into the DSL; you can edit and refine your collections and rerun past searches.

 

Upload your own texts
---------------------

([back to table of contents](#table of contents))

You're not limited to Gale's selection of texts: there are three options whereby you can upload texts of your own and analyze them in the DSL. There are three methods, each described below:

* [Create a text document](#upload_text_doc)
* [Bulk upload, method 1: text files](#upload_bulk1)
* [Bulk upload, method 2: spreadsheet (CSV)](#upload_bulk2)

Each of these methods is described below.

*Note: Do not upload in\-copyright texts or texts with sensitive or personal information.*

### Create a text document

([back to table of contents](#table of contents))

1. Let's try it!**Begin by clicking on Build in the top toolbar.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_001.png' | relative_url }}' alt='Digital Scholar Lab main page with Build highlighted in the top menu.' title='' width='800' height='473' />
2. On the right side, there is the Upload box. There are two ways to upload texts: by inputting text directly into DSL or by uploading multiple files simultaneously. We'll try both, but we'll begin with the simpler method.**At the top of the Upload box, click on Create a Text Document.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_002.png' | relative_url }}' alt='The Build page with Create a Text Document highlighted under Upload.' title='' width='800' height='370' />
3. The Text Entry page has a number of fields. Only the Title and Text fields are necessary, but the other fields are useful, both because they help keep your texts organised and because some of the metadata, such as year and date, are necessary for certain tools.**Begin by pasting the following text into the Title and Text fields:** 
Title:  
`Preface`  
Text:  
`In the introductory remarks prefixed to this Memoir I have endeavoured to indicate briefly the objects and methods which guided me in the surveys of my three Central-Asian journeys and in the preparation of the maps which contain their final cartographical record.`  
`It only remains for me to acknowledge with gratitude my manifold obligations for the effective help which alone rendered possible the topographical tasks bound up with my explorations.`  
`That I was able to plan and carry out those tasks was due to the fact that the Survey of India, accustomed ever since its inception to serve the interests of Help of^nney of geographical research, not only within the vast area forming its own sphere of activity but also beyond the borders of India, supported from the start my aims with the means best suited for them. In Chapter 1, dealing with the history of our surveys, I have had occasion fully to note the services rendered by the experienced Indians whom the various Surveyor Generals deputed with me, and the extent of the help which I received by the provision of instruments, equipment arul funds to meet the cost of their employment. To the Survey of India was due also the compilation and publication of the results brought back by our joint efforts from each successive journey.`  
`The topographical results thus secured have not only helped me to make my journeys directly profitable for geographical study, they have also greatly facilitated my archaeological explorations in regions which, though largely desolate today in their physical aspects, have yet played a very important part in the history of Asia and its ancient civilizations. But apart from the gratitude I owe for this furtherance of my researches, the fact of my having been able to work in direct contact with the oldest of the scientific departments of India will always be remembered by me with deep satisfaction.`  
`Ever since in 1899 the proposals for my first Central-Asian journey had received the Government of India's sanction, successive Surveyor Generals did .Surveyor^euorals tlieir best to facilitate the survey tasks of my expeditions. 1 still`  
`think back gratefully to the very helpful advice and instruction by which the late Colonel St. Georg Gore, R.E., while at Calcutta during the cold weather of 1899-1900, showed his personal interest in the enterprise. His successor as Surveyor General, Colonel F. B. Long, R.E., was equally ready to meet my requests concerning the plans !. had formed for my second and much more extensive expedition of 1906-08.`  
`But my heaviest debt of gratitude is due to Colonel Sir Sidney Burrard, RE.,`  
`K.C.S.I., F.R.S., who as Superintendent of the Trigonometrical Survey SidneyCBnrrnrd since 1899 had direct charge of all arrangements for the survey work of my first and second expeditions, and who during his succeeding long term of office as Surveyor General was equally ready to extend to me unfailing support and guidance with regard to the third. Moreover quite as great a stimulus was the thought of his own lifelong devotion to the study of the geographical problems connected with innermost Asia and the great mountain systems which enclose it. I feel hence very grateful for being allowed to dedicate this record of our labours to Sir Sidney Burrard not merely as a most helpful friend and guide but also as a living embodiment of that spirit of scientific research which has never ceased to pervade the Survey of India since the days of Rennell, Lambton, and Everest.`  
<img src='{{ '/assets/images/DSL_Collections_Upload_003.png' | relative_url }}' alt='Document Editor with the text provided in the tutorial pasted into the Title and Text fields, both highlighted.' title='' width='800' height='596' />

    *Note: you have probably noticed that there are some misspellings and other errors in the text above. This is because this text was made by using an OCR algorithm on scanned images of pages. These OCR errors are, unfortunately, a common byproduct of this process, requiring considerable time to manually check for even a single text, let alone the hundreds or thousands of texts in a collection. (I removed a small number of illegal characters, including variations on the apostrophe, to make this text compatible with DSL's requirements.) This is also a fairly error\-free example. I took this text from Stein's 1923*Memoir on Maps of Chinese Turkistan and Kansu,*specifically*[*this copy of Stein's text from the Internet Archive*](https://archive.org/details/dli.csl.7301)*.*
4. Now let's begin adding metadata.  
<img src='{{ '/assets/images/DSL_Collections_Upload_004.png' | relative_url }}' alt='Document Editor with the text provided in the tutorial pasted into the metadata fields, all highlighted.' title='' width='800' height='591' />

 **For each of the following fields, add the following metadata:** 
 **Author:**Aurel Stein K. C. I. E.  
 **Publication Title:**Memoir on Maps of Chinese Turkistan and Kansu  
 **Publisher:**Trigonometrical Survey Office  
 **Document Type:**Chapter  
 **Language:**English  
 **Subject:**Geography
5. **Click on the Publication Date field.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_005.1.png' | relative_url }}' alt='The Publication Date field highlighted.' title='' width='400' height='572' />

    You can type in your date manually, or you can use the calendar. The calendar window looks different depending on which web browser you are using. Click the Month/Date menu at the top.  
        <img src='{{ '/assets/images/DSL_Collections_Upload_005.2.png' | relative_url }}' alt='Drop-down menu for selecting date with the month and year menu at the top highlighted.' title='' width='400' height='545' />

 **From the month dropdown menu, select January 1923\.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_005.3.png' | relative_url }}' alt='Month and Year menu with Jan 1923 selected and highlighted.' title='' width='400' height='584' />

 **In the month view, click on the 1st. When you click out of the calendar, the Publication Date should read 01/01/1923\.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_005.4.png' | relative_url }}' alt='The Publication Date field highlighted, with the date set to 01/01/2023.' title='' width='400' height='569' />

    *Note: we only have the year of publication for this text, but DSL requires a full date, with day and month, for their data. For this reason, we added January 1st, even though in practice you can ignore the month and day.*
6. This text should now have all of its metadata fields complete.**Click on the Create Document button at the bottom to upload the text.**A banner stating "Document Saved" should briefly appear.  
<img src='{{ '/assets/images/DSL_Collections_Upload_006.png' | relative_url }}' alt='Document Editor with Create Document highlighted.' title='' width='800' height='559' />

    *Note: metadata is "data about data," or more specifically, it is information about a dataset (whether that dataset is a book, article, film, image, etc.) such as the author and publication year. It is used by several of DSL's tools (e.g. the Parts of Speech tagger compares the styles of different authors, so it needs texts to have their Author fields filled out). We used "Aurel Stein K. C. I. E." because spelling his name differently, even if it would be recognizable as the same person to a human, will be technically a different author for any computational tools. This particular formulation is one of the existing variations in DSL and is how Stein wrote his name on the title page, so it works best.*
7. **Now that this text has been uploaded, let's add it to our collection for further analysis. Click on Add to Content Set.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_007.1.png' | relative_url }}' alt='Document Editor with Add to Content Set highlighted.' title='' width='800' height='523' />

 **From the menu, select Stein.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_007.2.png' | relative_url }}' alt='Document Editor with Add to Content Set drop-down menu open and Stein highlighted.' title='' width='800' height='528' />

 **Once DSL confirms that this text has been added to the Stein collection, click Close.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_007.3.png' | relative_url }}' alt='Updated Content Set pop up window with close highlighted.' title='' width='400' height='180' />
8. Let's see where we can review these uploaded texts.**Click on Manage Uploads.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_008.1.png' | relative_url }}' alt='Document Editor with Manage All Uploads highlighted.' title='' width='800' height='523' />

    This opens up the Manage All Uploads page. Here you can see a list of all texts you have uploaded. So far, we only have one, but we will add more soon. You can also use this page to add texts to content sets, apply metadata after uploading them, or to delete them.  
        <img src='{{ '/assets/images/DSL_Collections_Upload_008.2.png' | relative_url }}' alt='Manage All Uploads page.' title='' width='800' height='321' />

 

### Bulk upload, method 1: text files

 

([back to table of contents](#table of contents))

1. Next we'll explore another method of uploading texts, one that can handle bulk uploading of texts. **Click on Build.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_008.3.png' | relative_url }}' alt='Digital Scholar Lab main page with Build highlighted in the top menu.' title='' width='800' height='473' />
2. **First, download these two .txt files by right clicking on the links below and saving them each to your computer (selecting Save Target As or Save Link As):** 
[download Introductory material](https://maps.library.utoronto.ca/workshops/GaleDLS/introductory.txt)  
[download Chapter 1, Section 1](https://maps.library.utoronto.ca/workshops/GaleDLS/section1.txt)  
**In the Upload box, click Browse.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_009.1.png' | relative_url }}' alt='The Build page with Browse highlighted under Upload.' title='' width='800' height='370' />

 **Navigate to where you downloaded these files, select both of them (hold down CTRL (Windows) or CMD (Mac) to select more than one item at a time), and click Open.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_009.2.png' | relative_url }}' alt='File browser with the two text documents provided in the tutorial selected and highlighted, with open highlighted.' title='' width='600' height='427' />

    *Note: the example above comes from a PC. Your interface may look different.*
3. You will be brought back to the Manage All Uploads page, where you can see the two texts you just uploaded at the top and in bold. The date uploaded will say “Just Now”. Notice how there is no metadata for either of these new uploads. We can add that now. **Check the box next to each and click the Edit Metadata button.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_010.png' | relative_url }}' alt='Manage All Uploads page with the two new files selected and Edit Metadata highlighted.' title='' width='800' height='378' />**
4. In the Apply Metadata window we have two options: Bulk and Individual. Bulk is selected by default and will let us apply the same metadata to both files we have selected. **Leave it selected on Bulk.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_011.1.png' | relative_url }}' alt='Apply Metadata window with Bulk highlighted.' title='' width='500' height='494' />**

    Then, **add the metadata** as before:

 **Author:**Aurel Stein K. C. I. E.  
 **Publication Date:**01/01/1923  
 **Publication Title:**Memoir on Maps of Chinese Turkistan and Kansu  
 **Publisher:**Trigonometrical Survey Office  
 **Document Type:**Chapter  
 **Language:**English  
 **Subject:**Geography

    Finally, **click Apply Metadata.** 
 **<img src='{{ '/assets/images/DSL_Collections_Upload_011.2.png' | relative_url }}' alt='Apply Metadata window with the metadata fields filled in and highlighted.' title='' width='500' height='496' />**
5. The metadata have now been applied! But we still need to add these new texts to a collection. **Check the box next to each and click on Add to Content Set.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_012.1.png' | relative_url }}' alt='Manage All Uploads page with the two new files now with complete metadata, both selected and Add to Content Set highlighted.' title='' width='800' height='470' />**

 **From the drop\-down menu, select Stein.** 
 **<img src='{{ '/assets/images/DSL_Collections_Upload_012.2.png' | relative_url }}' alt='Add to Content Set drop down menu with Stein highlighted.' title='' width='700' height='357' />**
6. One final method to apply metadata is to use a spreadsheet. This method is best if you are uploading multiple texts with different metadata.**Begin by saving these texts to your computer:** 
[download khotan.txt](https://maps.library.utoronto.ca/workshops/GaleDLS/khotan.txt)  
[download panoramas\_introductory\_note.txt](https://maps.library.utoronto.ca/workshops/GaleDLS/panoramas_introductory_note.txt)  
We’re going to upload these texts the same way we uploaded the previous ones. **Go to the build page, then, in the Upload box, click Browse.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_013.1.png' | relative_url }}' alt='The Build page with Browse highlighted under Upload.' title='' width='800' height='370' />**

 **Select both of the new files and click Open.** 
 **<img src='{{ '/assets/images/DSL_Collections_Upload_013.2.png' | relative_url }}' alt='File browser with the two new text documents provided in the tutorial selected and highlighted, with open highlighted.' title='' width='700' height='494' />**
7. As with before, **select those the two new .txt files from the Manage Uploads list, and then click on Edit Metadata.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_014.png' | relative_url }}' alt='Manage All Uploads page with the two new files selected and Edit Metadata highlighted.' title='' width='800' height='352' />**
8. This time, in the Apply Metadata window we are going to use the Individual option. **Select Individual.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_015.png' | relative_url }}' alt='Apply Metadata window with Individual highlighted.' title='' width='500' height='496' />**
9. Next, **click on Download Form.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_016.png' | relative_url }}' alt='Apply Metadata window with Download Form highlighted.' title='' width='500' height='496' />**
10. Depending on your internet browser settings, you might automatically download a file called*metadata\-template.csv.***If you are prompted to download it, choose where you would like to download it and then click save.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_017.png' | relative_url }}' alt='Download file popup.' title='' width='500' height='368' />**
11. **Open up the file** in a program like Excel, Numbers, or OpenOffice Calc.  
**<img src='{{ '/assets/images/DSL_Collections_Upload_018.png' | relative_url }}' alt='Metadata.Template.csv opened in excel.' title='' width='700' height='386' />**
12. By using a spreadsheet, you can upload metadata for multiple texts quickly, and unlike the Quick mode, you can give different metadata for each text. This method is especially useful if you have bibliographic information for many documents available from another source, like that which might be exported from bibliographic software like Zotero, Mendeley, or RefWorks.  
**Input the following data into the spreadsheet:**

 ***for khotan.txt*** 
 **Title:**Sand Buried Ruins of Khotan \- Chapter IV  
 **Author:**Aurel Stein K. C. I. E.  
 **Publication Date:**01/01/1904  
 **Publication Title:**Sand Buried Ruins of Khotan  
 **Publisher:**Hurst and Blackett  
 **Document Type:**Chapter  
 **Language:**English  
 **Subject:**Archaeology

 ***for panoramas\_introductory\_note.txt*** 
 **Title:**Mountain Panoramas from the Pamirs and Kwen Lun \- Introductory Note  
 **Author:**Aurel Stein K. C. I. E.  
 **Publication Date:**01/01/1908  
 **Publication Title:**Mountain Panoramas from the Pamirs and Kwen Lun  
 **Publisher:**Royal Geographical Society  
 **Document Type:**Chapter  
 **Language:**English  
 **Subject:**Geography

 **<img src='{{ '/assets/images/DSL_Collections_Upload_019.png' | relative_url }}' alt='Metadata.Template.csv opened in excel with all fields filled out.' title='' width='800' height='289' />**

 ***Important notes:*** 
        *Do not change any information in the Document ID column, or DSL will be unable to process the data. The Document ID number is different every time you upload a file, even if you upload the same file more than once.*  
        *The Publication Date column only works if the date is in the format DD/MM/YYYY, like 01/01/1904 for the first of January, 1904\. As above, you will have to add days and months for the upload to work, even if the original publication only had a year of publication.*  
        *The texts might be in a different order for you than I have listed them. Be sure to match the data to the right row or you'll end up with texts that have the wrong title and year.*
13. **Save the spreadsheet. Be sure to save it in .CSV format (which is the format it comes in).**Some programs like Excel will ask you to save in another format, but you must save it as a .CSV for DSL to recognise it.
14. With the file saved, go back to your web browser. **In the Apply Metadata window, click on Browse.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_021.png' | relative_url }}' alt='Apply Metadata window with Browse… highlighted.' title='' width='500' height='494' />**
15. **Navigate to where you have saved your completed metadata form, select it, and click Open.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_022.png' | relative_url }}' alt='File browser with your completed and saved metadata form selected and highlighted, with open highlighted.' title='' width='700' height='494' />**
16. Now that we see our csv filename next to Choose file, **click on Apply Metadata.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_023.png' | relative_url }}' alt='Apply Metadata window with Apply Metadata highlighted.' title='' width='500' height='496' />**
17. You will then return to the Manage All Uploads page. The two newly added texts, with their metadata, will now be there. **Check the boxes next to "Sand\-Buried Ruins of Khotan" and "Mountain Panoramas..." and click on Add to Content Set.** 
**<img src='{{ '/assets/images/DSL_Collections_Upload_024.1.png' | relative_url }}' alt='Manage All Uploads page with the two new files now with complete metadata, both selected and Add to Content Set highlighted.' title='' width='800' height='530' />**

 **Select Stein. Close the popup that appears.** 
        <img src='{{ '/assets/images/DSL_Collections_Upload_024.2.png' | relative_url }}' alt='Add to Content Set drop down menu with Stein highlighted.' title='' width='500' height='255' />

 

### Bulk upload, method 2: spreadsheet (CSV)

([back to table of contents](#table of contents))

Third, if you are comfortable working in a spreadsheet, you can efficiently bulk upload*short*documents with their metadata in one file. Each row in your spreadsheet will become one document, with both its text and metadata.

1. **Click on Build.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_008.3.png' | relative_url }}' alt='Digital Scholar Lab main page with Build highlighted in the top menu.' title='' width='800' height='473' />
2. Click**Get Upload Template.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_030.png' | relative_url }}' alt='Upload panel with Get Upload Template highlighted' title='' width='1241' height='561' />
3. You will download a zipped file called **"DSLAB\-Upload\-Instructions.zip"; unzip this package to a new folder.** (We recommend [7\-zip](https://www.7-zip.org/) if you are using Windows).  
<img src='{{ '/assets/images/DSL_Collections_Upload_031.png' | relative_url }}' alt='Unzipping the upload template' title='' width='800' height='487' />
4. In the newly created folder, you will find instructions (DSLAB\-Upload\-Instructions.pdf) and a template (DSLAB\-Upload\-Template.csv).**Open DSLAB\-Upload\-Template.csv.** 
<img src='{{ '/assets/images/DSL_Collections_Upload_032.png' | relative_url }}' alt='Selecting the Upload Template' title='' width='500' height='80' />
5. Copy and paste your text into the column labelled**Text.** 
*Note: cells in CSVs have a maximum length of 32 767 characters, which is roughly 5000 words. Texts longer than this limit will be shortened. For longer texts,* [*upload one or more .txt files directly.*](#upload_bulk1)  
<img src='{{ '/assets/images/DSL_Collections_Upload_033.png' | relative_url }}' alt='Upload template in Excel' title='' width='800' height='413' />
6. **Fill in the rest of the metadata such as author and title.** 
If you wish, you can [download this sample completed CSV](https://maps.library.utoronto.ca/workshops/dsl/DSLAB-Upload-Template-Edited.csv).  
*Note: although the DSL asks for day, month, and year for the Publication Date column, you can simply put a year if the precise day of publication is uncertain. The DSL will automatically input the value of January 1st for each row.*  
<img src='{{ '/assets/images/DSL_Collections_Upload_034.png' | relative_url }}' alt='Template with text and publishing information for two poems' title='' width='800' height='289' />
7. **Save and upload your completed CSV**, either by dragging the file into the Upload area or clicking Browse and selecting your file.  
<img src='{{ '/assets/images/DSL_Collections_Upload_035.png' | relative_url }}' alt='Dragging and dropping the CSV into the Upload pane' title='' width='800' height='348' />
8. Each row is now an individual text, which you can add to collections and analyze.  
<img src='{{ '/assets/images/DSL_Collections_Upload_036.png' | relative_url }}' alt='Manage All Uploads section of the DSL with the new texts added' title='' width='800' height='308' />

That's it! You now know how to build your DSL collection with advanced searches and through uploads.

[Proceed on to Cleaning](https://mdl.library.utoronto.ca/technology/tutorials/digital-scholar-lab-cleaning)  
[Return to the main Gale Digital Scholar Lab tutorial](https://mdl.library.utoronto.ca/technology/tutorials/digital-humanities-tools-digital-scholar-lab)

Technique: [Text and Data Mining](/technique/text-and-data-mining), [Searching for maps and data](/technique/searching-maps-and-data) \| Tools: [Digital Scholar Lab](/tools/digital-scholar-lab-0)**Date Created:** 2022\-03\-10**Updated:** 2025\-02\-21
