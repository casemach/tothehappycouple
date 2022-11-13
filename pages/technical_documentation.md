---
title: Technical Documentation
layout: about
permalink: /tech.html
---

{% include feature/jumbotron.html objectid="/assets/img/featured_image.jpg" %}

## Technical Documentation

{% include feature/nav-menu.html sections="Items Chosen;Imaging Standards;Metadata Standards" %}

## Items Chosen 

The items in this collection were chosen because they are owned by a family member of the creator who gave permission for the collection to be digitized for this project. All items have been fully digitized. Items that are a single page have been uploaded as JPG images and items that are multiple pages have been uploaded as PDFs. 

## Imaging Standards 

The items in this collection were scanned using an Epson Perfection V550 Photo Color Scanner and saved as TIFFs to the creator's personal laptop. The TIFFs were 300 dpi. All items were then converted to JPGs on the highest quality setting using Adobe Acrobat. Multi-page items were converted from JPGs to PDFs using Adobe Acrobat. No color adjustments were made to the images. 

## Metadata Standards 

The metadata for this project is important for creating site functionality and accurately representing the features of the items for the benefit of site users. The metadata scheme uses elements from Dublin Core and CollectionBuilder-GH. The values of individual elements are subject to established controlled vocabularies and content standards such as Library of Congress Subject Headings and Internet MIMEType. 

Listed below are Dublin Core elements and their use in the metadata scheme for this collection.  

*Title - required, 1 value allowed 

Titles are the name assigned to each object. The names are assigned by the creator of digital collection. The title should describe the object, such as people or place in the photograph, or senders and recipients of a card. 

Examples: Card from Alberta Stall to the Machenheimers, 1961; Elizabeth Stratman at bridal shower, 1961

### _Date - required, 1 value allowed_ 

The date when the object is from. All objects are from the year 1961. The bridal shower took place on September 24, 1961 and the wedding took place on November 4, 1961. Unless it is explicitly stated on the object, only the year is written as the date since it is known. Dates are formatted based on the [W3c date format](https://www.w3.org/TR/NOTE-datetime): 
* YYYY 
* YYYY-MM
* YYYY-MM-DD

Example: 1961-09-24 to denote September 24, 1961

*Description - required, 1 value allowed 

The description is used to describe the object, including the physical description, the date, and who/where/what is depicted. Description is determined by the object itself. If it is a photograph, the description is of where, when, and who is depicted. If it is a card, the description is of the cover of the card, the sender(s), and the receiver(s) of card. For any other objects, a general description of physical attributes or other pertinent information is provided. 

Example: This object is a card sent to Harry Machenheimer and Suzanne Stratman from Ruth Geglein for their bridal shower on September 24, 1961. The front of the card states, “For Your Bridal Shower” and depicts two silver bells decorated with silver ribbon, silver laurel, pink roses, and green leaves. 

*Subject - required, multiple values allowed 

The subject is one or more descriptors used to identify the object. This is genereated as a word cloud on CollectionBuilder-GH to provide a way for users to browse the digital collection. Subjects are determined by the object itself. Most of the subjects are determined based on the [Library of Congress Subject Heading (LCSH)](https://www.loc.gov/aba/publications/FreeLCSH/freelcsh.html). Other subjects include the names of the publishers, senders, and receivers of the cards. 

Examples: 
* American Greetings Corp 
* wedding cards 
* wedding decorations

*Publisher - required if present, 1 value allowed 

The publisher is the company or institution responsible for the creation of the design and text of the greeting card. Publishers are listed on the back cover of the cards at the bottom. For the metadata, the full name of the publisher of the card is listed (even if in public domain).

Example: American Greeings Corp

*Contributor - required if present, multiple values allowed 

Contributor is the Dublin Core element used to identify both the senders and receivers of the cards, bridal shower invitiation, and letter. Senders and Receivers are listed as separate elements in the metadata scheme. The format for both senders and receivers is to give the last name, the first name, and the middle name or initial (if known), as well as the date of birth and/or date of death (if known). 

Examples: 
* Young, Janet 
* Machenheimer, Harry, 1937-
* Machenheimer, Suzanne Stratman, 1939-2012

*Format - required, multiple values allowed 

The format has four required values: digital file format, physical format, dimensions, and number of pages. For digital file format, terms are taken from the [Internet MIMEtype](https://www.iana.org/assignments/media-types/media-types.xhtml) and follow the format shown in the examples. All the items in the collection are TIFFsThe physical format is a short phrase in lowercase letters describing the object. The dimensions are width x length for two-dimensional objects and width x length x depth for three dimensional objects. They are measured in inches. The number of pages are listed as a number followed by “pp.”  

Examples: 
* Digital file format 
  * image/jpeg
  * application/pdf
* Physical format:  
  * folded cardstock  
  * black-and-white photograph  
* Dimensions:
  * 5in x 7in  
  * 4in x 8in x 2in  
* Number of pages:   
  * 1 pp
  * 3 pp

*Rights - required, 1 value allowed 

The rights field describes the copyright status of each object and/or the copyright holder (if applicable). The cards are all part of the public domain. All other objects are owned by a third party (Harry Machenheimer), who has given permission to digitize this collection. For personal photographs, copyright is listed as owned by a third party, as shown in the example. If it has entered the public domain, the copyright will be listed as “public domain.”

*Identifier - required, 1 value allowed 

This field uniquely identifies each field in the digital library. It is listed as object type, underscore, sender (if applicable), underscore, receiver (if applicable), underscore, date, underscore, a number, and then the file extension.

Examples: card_stratman_machenheimer_1961_001; photo_1961_09_24_005
