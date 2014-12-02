vnote
=====

A new way to share and import notes. Since the advent of mobile devices we have seen many note taking applications like Evernote, Omni-Notes, Keep, Hashnote, the list never seems to end. The main problem faced is the sharing of notes, if you have to share it to an app in your phone then it simply shares the text, but if you try sharing a note between devices, it shares it in a html webpage, which isn't at all convenient. 

Vnote is an attempt to put an end to such miseries. It is inspired from the concept of vCard which stores contact details. The beauty of vCard is you can easily export all your phone book from any phone and import it in any other phone as well. That function is *lacking* in modern note taking apps which create a niche for themselves. This will make the job of importing and exporting notes easier.

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
