vnote
=====

A format to store notes, inspired from vcard.

With the advent of mobile devices there have come a plethora of note taking applications, each of them has their advantages as well as their own shortcomings, but sharing notes among each application is a cumbersome task. This specification takes inspiration from vcard. 

This will make it easier to share and import notes from various applications into any application that supports this specification, thus allowing interoperability among various note taking applications.

**components**

1. `<vnotes>` : the root tag that contains one or more `<vnote>` tags
2. `<vnote>`  : the tag that stores one note
3. `<title>` : the tag that saves the title of the note
4. `<content>`: the tag that saves the content of the note
5. `<text>`: used when you have to store plain text
6. `<uri>`: used when you have mobile number or a link to store
7. `<list>`: used when you have to store a list
   type= "unordered" or "numbered" 
8. `<element>`: member of a list
9. `<checkbox>`: stores checkboxes
    type="checkboxes"
10. `<cbelement>`: member of a checkbox
    type="checked" or "unchecked", default is unchecked
11. `<timestamp>`: the timestamp or the date when the note was taken
12. `<last-updated>`: the timestamp or date when the note was last updated
