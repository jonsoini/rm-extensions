# Outline, and other rm-extensions

**Note: Outline is currently built and tested only on the reMarkable Paper Pro Move. It is not ready for other reMarkable devices quite yet.**

This repo contains my extensions to make the remarkable tablets better. 

The first extension, is Outline. It adds key organization features for your documents: 
- Headings
- Keywords
- Star recognizer (experimental)
- Full document linking capability

I have more extensions planned... stay tuned.

## Outline for Remarkable
Outline is a 3rd party very unofficial addon for your Remarkable tablet that adds a few key features:

- Headings  
- Keywords  
- Star detection for drawn stars  
- Links, both in and between documents

I was tired of my Remarkable not having these things but very much like the other aspects of it, so here we are. The missing organization features you’ve probably wanted. 

New toolbar and lasso bar elements:

\[TODO image\]

There’s a new icon, close to where ‘Redo’ is (it may replace Redo and push it to the overflow menu if you have a Move). 

Tapping this opens the navigation panel so you can quickly get to any heading, keyword or star.

\[TODO image lasso\]

The lasso menu has new items for \[H\]eading, \[K\]eyword or 🔗Link.

### Headings

\[TODO image\]

You can lasso any hand drawn element and store that as a navigable heading for your document. Works best with horizontal rectangular shapes. Headings are listed by page number, then document order.

Once stored you can navigate back to any heading by tapping it. Headings can also be link targets. 

### Keywords

\[TODO image\]

(Requires a cloud subscription or rmfakecloud)

Lasso any word(s) to have the text recognized and stored as a keyword. You can use the same word across many pages to see every place it’s used.

### Stars

\[Experimental\] Outline will attempt to recognize star shapes in your documents and will show you a list of them including colors used.

Stars must be drawn in a single stroke, five-sided stars are supported. 

Outline will occasionally refresh its star database as you create and remove them. 

### Links

Outline lets you create and manage links for hand-drawn elements. **Links are navigated by touch, not pen**.  

Links will appear on a page with a dashed box outline and an icon in the upper right which gives you clues as to whether the link is for the current document or another document and its action.

You can link to any of these things:

- Headings  
- Keywords  
- \[1\] First page of a document  
- \[\>\] Latest page of a document  
- \[+\] *Action to create a new page in a document*  
- Soon, an arbitrary page

You can link to things within the current document or other documents\! Link targets within the current document are a lighter icon color while links to other documents get a dark background.

TODO image of links

The action of creating a new page will give that link functionality to create a new page and jump there, useful for quickly creating daily notes or the latest project update. It will create a new page every time you tap the link\! 
