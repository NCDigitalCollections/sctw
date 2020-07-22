About page:

About page instructions are on the new about page. You can also refer to our documentation for guidance: <https://collectionbuilder.github.io/docs/finish.html#about-page>, watch the tutorial here: <https://collectionbuilder.github.io/workshop/gh/finish.html>, or just ask me if you have questions!
 
Feature select jpegs but view all in gallery:

<https://ncdigitalcollections.github.io/ncdctest/items/coll042.html> and <https://ncdigitalcollections.github.io/ncdctest/items/coll060.html> - examples of being able to feature a small number of images but view them all in the gallery view. I picked out these featured images just to provide an example (I added featured image numbers to the "compound" column). If you don't want featured images, and just want the first image to show up, simply delete all the values from the "compound" cell for this record.
 
Add transcriptions:

<https://ncdigitalcollections.github.io/ncdctest/items/coll000.html> and <https://ncdigitalcollections.github.io/ncdctest/items/coll060.html> - examples of transcriptions (they show up under the item on the left side of the page—note they're not the real transcriptions, just text I pulled from one of our collections). To add a transcription to an object (this will work for any kind of object; image, pdf, audio, or video), you'll need to add the value "true" to the new column titled "transcription" (this is the last column in the spreadsheet right now, I just added it). Then, you'll need to create the transcription in the _includes/transcriptions folder. These files should be markdown (.md) files. You can see the two examples in the folder already. The most important thing is to name these files with their record's corresponding objectid. Then you can style the text however you want using markdown. Here's an introduction to markdown if you need it: <https://commonmark.org/help/tutorial/>.
 
View pdfs as embeds in item page:

Many of the pdfs in this collection are very large, so I noticed that they do take a long time to load. For this reason, I made this a feature that you can turn on and off. You'll use the theme.yml file to do it: scroll down to ITEM PAGE and then you can change the value of `pdf-embed` to true or false. If true, pdfs will display as embedded into the page and the user can scroll through the pdf pages. If false, only the first page of the pdf will display, as a thumb, and the user can click on the Download PDF button to view the whole pdf in another browser tab.
 
GitHub Actions instructions:

I created some documentation here: <https://github.com/NCDigitalCollections/sctw/blob/master/docs/gh-actions.md>. If it's not clear or if you run into trouble just let me know!
 
Audio items:

This is set up to pull from Internet Archive now. See <https://ncdigitalcollections.github.io/ncdctest/items/coll047.html> as an example. It still needs some work visually, but it's functional now and I'll work more on the aesthetics. In order for this to work, you'll have to add a value to a new column I created in the metadata, titled ia_identifier. For all your audio files, you'll need to grab the identifier that's at the end of the archive.org/details url and add this value to this column. Example: for `https://archive.org/details/MilCollOH1131Blue` the identifier is `MilCollOH1131Blue`.
 
Sorting on the browse page:

You can now sort items on the browse page, using the "Sort by" button. You can customize which fields to sort by on the config-browse.csv. I added a new column titled "sort_name". If you give this column a value, the field will appear in the "Sort by" dropdown.