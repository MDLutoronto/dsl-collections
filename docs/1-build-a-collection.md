---
title: Build a Collection
parent: Digital Scholar Lab - Collections
layout: default
nav_order: 1
---

## Build a Collection

The DSL has access to [Gale's extensive digital collections](https://www.gale.com/primary-sources) of newspapers, books, and other archival material. In this tutorial, we will focus on texts by and about an early twentieth-century scholar named [Sir Aurel Stein](https://en.wikipedia.org/wiki/Aurel_Stein), who travelled throughout South and Central Asia and China as an agent of the British Empire. There are many materials related to him - works by him, newspaper articles about his expeditions, etc. - available in the DSL, mostly ranging from the 1920s to the 1940 from a variety of newspapers (*The* *London Times*,*Illustrated London News*,*The Daily Mail*,*The New York Times*) and other digitised holdings from libraries and archives (the British Library, the Smithsonian, the American Antiquarian Society, the National Library of China).

1. When you’re logged in ([instructions for logging in](https://mdl.library.utoronto.ca/technology/tutorials/logging-digital-scholar-lab-through-catalog)), you will need to create your corpus (the collection of texts on which you will run statistics on and create visualizations). To access the search bar, click on **Build** in the top-right navigation bar.<img src='{{ '/assets/images/DSL_Collections_Build_001.1.jpg' | relative_url }}' alt='Digital Scholar Lab main page with ‘Build’ in the navigation bar highlighted.' title='' width='800' height='578' />

    Although you can use the search bar on the left of the page to get started with a basic search, let’s use the advanced search for a little more precision. **Click on View all limiters in Advanced Search under the search bar.** 
        <img src='{{ '/assets/images/DSL_Collections_Build_001.2.png' | relative_url }}' alt='The Build page with ‘View all limiters in Advanced Search’ highlighted under the main search bar.' title='' width='800' height='480' />
2. You will arrive at the Advanced Search page.  
<img src='{{ '/assets/images/DSL_Collections_Build_002.png' | relative_url }}' alt='Advanced Search page.' title='' width='800' height='512' />

    It is structured like a library catalogue search page. You can use Boolean operators like AND, OR, and NOT to create complex search queries. Gale also automatically suggests [metadata](https://en.wikipedia.org/wiki/Metadata) (e.g. authorship, publication date, language) from their collection as you type.
3. The build page is the first screen where you can view DSL's learning videos. Feel free to watch these as you complete these steps to get an introduction to the features available on that page.  
<img src='{{ '/assets/images/DSL_Collections_Build_003.jpg' | relative_url }}' alt='The build page with the tutorial video highlighted.' title='' width='800' height='499' />

4. Let’s search for Aurel Stein as an Author. **Begin by clicking on the dropdown menu on the right of the first field.** 
<img src='{{ '/assets/images/DSL_Collections_Build_004.png' | relative_url }}' alt='Advanced Search page with the Field drop-down menu highlighted.' title='' width='800' height='264' />

5. **Change it from Keyword to Author.** 
<img src='{{ '/assets/images/DSL_Collections_Build_005.png' | relative_url }}' alt='Advanced Search page with the Field drop-down menu open and Author highlighted.' title='' width='800' height='324' />

6. **Then, click in the search bar and type Aurel Stein.**

    Once you start typing his name, if you have “Author” selected as the search field, you will see at least four different variations of his name appear.

    **Select the first option, “Aurel Stein K. C. I. E.”.** 
            <img src='{{ '/assets/images/DSL_Collections_Build_006.png' | relative_url }}' alt='Advanced Search page with the Terms being filled in.' title='' width='800' height='383' />

    *Note: DSL automatically suggests metadata like author names from its collections, but only if the correct field (e.g. author, keyword) is selected first. Because different databases have input Stein's name differently, there are four variations of his name and thus four different "authors" when searching. Although this is not ideal, it is common when working with data aggregated from many places. Let’s say that we want everything written by Stein, regardless of how his name appears in the various databases.*
7. Because are four variations of his name and we want texts that are attributed to any of them, we will use an OR operator. **Click on the left dropdown menu and select OR.** 
    <img src='{{ '/assets/images/DSL_Collections_Build_007.png' | relative_url }}' alt='Advanced Search page with the search row operation set to OR.' title='' width='800' height='260' />

    **Then, repeat the above steps, first changing Keyword to Author, then typing Aurel Stein, and selecting the next variation on his name.**

8. Since there are four variations of his name, we need more than three search terms. **Click on Add a Row at the bottom to add a fourth row.** 
<img src='{{ '/assets/images/DSL_Collections_Build_008.png' | relative_url }}' alt='Advanced Search page with the ‘Add a Row’ button highlighted.' title='' width='800' height='324' />

9. Once you are done, there should be four lines joined with OR. **Click Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_009.png' | relative_url }}' alt='Advanced Search with the ‘Search’ button highlighted.' title='' width='800' height='322' />

10. You now see the search results page.  
<img src='{{ '/assets/images/DSL_Collections_Build_010.png' | relative_url }}' alt='Search result page.' title='' width='800' height='543' />

11. For each result, you will see its title, its author, its OCR Confidence Percentage (see the note below), and a preview of the text.  
<img src='{{ '/assets/images/DSL_Collections_Build_011.png' | relative_url }}' alt='The first search result, its author, OCR rating, ad sample text highlighted.' title='' width='800' height='543' />

12. Additionally, there is some metadata to the right, including the year of publication and the archive, source, and type of the text.  
<img src='{{ '/assets/images/DSL_Collections_Build_012.png' | relative_url }}' alt='The first search result’s publication and document information for highlighted. ' title='' width='800' height='543' />

    *Note: OCR refers to [Optical Character Recognition](https://en.wikipedia.org/wiki/Optical_character_recognition). It is a process whereby a program attempts to produce machine-readable text from a scanned document. The OCR Confidence percentage is an overall score that represents Gale’s confidence in the OCR quality of a specific text.*

    *One factor in their confidence level is the specific OCR algorithm used, since newer OCR algorithms typically perform more accurately than older ones. According to their documentation, over the nearly 20 years Gale has been collecting and scanning documents they have used a variety of OCR algorithms. Gale DSL currently uses Adobe Acrobat with ABBYY5 to OCR scanned documents.*

    *The OCR Confidence percentage additionally relies on other factors, such as the condition of the original document, the quality of the scan, what kind of text is featured in the document, and whether or not there are images in a document.*

    *A caution: the confidence level is useful but not perfect, as some documents can have a lower confidence than they deserve (if they feature lots of images), and some documents with high confidence can still include OCR mistakes. In other words, the confidence percentage is not a replacement for human attention. Some of the oldest scans won’t have a confidence percentage at all, since they predate that system.*
13. Let’s use all of these texts. **Click Select All.** 
<img src='{{ '/assets/images/Collections-13.jpg' | relative_url }}' alt='Search result page, with the ‘Select All’ selection box checked.' title='' width='800' height='484' />

14. **Then click Add to Content Set on the top-right corner.** 
<img src='{{ '/assets/images/DSL_Collections_Build_014.png' | relative_url }}' alt='In the search menu bar, ‘Add to Content Set’ highlighted. ' title='' width='800' height='543' />

15. **Select New Content Set.**     
<img src='{{ '/assets/images/DSL_Collections_Build_015.1.png' | relative_url }}' alt='Add to Content Set drop down menu with ‘+New content set’ highlighted.' title='' width='500' height='142' />

16. **Name it Stein and click Create. Close the notification that follows.**<img src='{{ '/assets/images/DSL_Collections_Build_016.png' | relative_url }}' alt='New Content Set window with ‘Stein’ written in the name field and the ‘Create’ button highlighted.' title='' width='500' height='215' />

17. Now, let's add some additional texts to this corpus. **On the main toolbar, click on Build.** 
<img src='{{ '/assets/images/DSL_Collections_Build_017.jpg' | relative_url }}' alt='Stein Content set page with ‘Build’ in the navigation bar highlighted.' title='' width='800' height='452' />

18. **Then, click on Advanced Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_018.png' | relative_url }}' alt='The Build page with ‘View all limiters in Advanced Search’ highlighted under the main search bar.' title='' width='800' height='468' />

19. The first time you used Advanced Search, you found texts **by** Aurel Stein. Now, let's look for texts **about** him, by searching for his name in the Keyword. **Just like with steps 3-7 above, type Aurel Stein into the search bar with Keyword selected this time, select one of the variations that occurs, and repeat with the next line.** 
<img src='{{ '/assets/images/DSL_Collections_Build_019.png' | relative_url }}' alt='Advanced Search page with the Terms being filled in and Field as keyword.' title='' width='800' height='392' />

20. **Like before, choose the three variations of his name. Be sure to use OR to separate all rows. And click on Search.** 
<img src='{{ '/assets/images/DSL_Collections_Build_020.png' | relative_url }}' alt='Advanced Search page with the search row operation set to OR and the ‘Search’ button highlighted.' title='' width='800' height='264' />

21. Now there are many more texts. The right sidebar menu offers ways of filtering this dataset. Just to keep our English-focused analysis consistent, Click on **Languages.** 
<img src='{{ '/assets/images/DSL_Collections_Build_021.1.png' | relative_url }}' alt='Search results page with the Languages filter highlighted.' title='' width='800' height='469' />

    Then **Click on English**, then **click Apply.**<img src='{{ '/assets/images/DSL_Collections_Build_021.2.png' | relative_url }}' alt='Search results page with the Languages filter open and the English selection box checked and highlighted.' title='' width='800' height='486' />
22. Let's add the remaining documents to our collection. **Scroll to the top of the page, click Select All. Then, click Select All (310) Results.** Remember, your document count may be different. <img src='{{ '/assets/images/DSL_Collections_Build_022.png' | relative_url }}' alt='Search result page, with the ‘Select All’ selection box checked and highlighted. ‘Select All Results’ also highlighted.' title='' width='800' height='528' />
23. **Add this to the content set you just created.** 
<img src='{{ '/assets/images/DSL_Collections_Build_023.png' | relative_url }}' alt='Add to Content Set drop down menu with ‘Stein’ highlighted.' title='' width='500' height='197' />

24. DSL automatically avoids adding duplicates to Content Sets. In this case the notification says that 293 (of 300) documents were added. Again, your number may be different. **Click Close.** 
<img src='{{ '/assets/images/DSL_Collections_Build_024.jpg' | relative_url }}' alt='Updated Content Set window with the ‘Close’ button highlighted.' title='' width='400' height='177' />

25. To view more information on a specific item, click it, and you will be taken to the Doc Explorer view. **Click the second item, "Sir Aurel Stein and Central Asia."** 
<img src='{{ '/assets/images/DSL_Collections_Build_025.png' | relative_url }}' alt='Search result page, with the title of one of the documents highlighted.' title='' width='800' height='659' />

26. You’ll see the document in its original context on the left, with the text highlighted and the keywords selected. You’ll also get the complete text file on the right. Under image properties, there are options to adjust brightness, contrast, and invert colours, and more.  
<img src='{{ '/assets/images/DSL_Collections_Build_026.jpg' | relative_url }}' alt='The Doc Explorer for the document selected.' title='' width='800' height='585' />

27. By scrolling down, you can see the scanned text on the left, with its text highlighted in light blue, and the specific keywords ("Aurel Stein") highlighted in green.  
<img src='{{ '/assets/images/DSL_Collections_Build_027.png' | relative_url }}' alt='Original document with highlighted name.' title='' width='800' height='900' />

28. Above, you have options to cite, download, email, and print the text. On the left you can open tabs for Explore, Table of Contents, and View Full Citation.  
<img src='{{ '/assets/images/DSL_Collections_Build_028.1.jpg' | relative_url }}' alt='Doc Explorer.  Above the option to ‘Cite’, ‘Send to’, ‘Download’, and ‘Print’ are highlighted. To the left the options to ‘Explore’, ‘Table of Contents’, and ‘View Full Citation” are highlighted. ' title='' width='800' height='585' />

    If you **click on “Learn how this text was created,”** you’ll receive basic information on Gale’s OCR process, and a link to further documentation.  
        <img src='{{ '/assets/images/DSL_Collections_Build_028.2.png' | relative_url }}' alt='Link for ‘Lean how this text was created’ highlighted.' title='' width='800' height='223' />
29. Let’s take a look at our collection. **Click on My Content Sets.** 
    <img src='{{ '/assets/images/DSL_Collections_Build_029.1.jpg' | relative_url }}' alt='‘My Content Sets’ in the navigation bar highlighted.' title='' width='600' height='376' />

    **Then click on Stein.** You’ll get an overview of where the texts in this corpus come from.  
            <img src='{{ '/assets/images/DSL_Collections_Build_029.2.jpg' | relative_url }}' alt='My Content Sets Page, with the Stein Content Set highlighted.' title='' width='800' height='418' />

30. To return to the list of texts, **click on the Documents button.** 
<img src='{{ '/assets/images/DSL_Collections_Build_030.jpg' | relative_url }}' alt='The Stein Content Set.' title='' width='800' height='491' />

    By clicking on Documents, you can view and manage the collection, removing texts if you wish. Having a collection means that you don’t need to rerun searches every time you log into the DSL; you can edit and refine your collections and rerun past searches.