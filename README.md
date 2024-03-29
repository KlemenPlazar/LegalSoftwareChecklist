﻿
# SmartCite

## Tweaks/changes
- [x] One major issue is that filenames are only recognized when they are extremely short and simple. E.g. Ex. 1 or a single word. In real life, filenames are often something like "Ex. 1 - [DESCRIPTION OF EXHIBIT]" or "2023-1-1 Ex. 1: Contract." See the ITC "Rename 2" folder--those are the actual filenames in use in this case. The software needs to be able to "look at" and recognize these filenames (or a part of them) appear in the main doc.
- [ ] ~~Would like page cites that refer to 2 pages or less of a cited document to appear in the scrollable window when scrolled over, as is currently possible with the paragraph symbol~~
- [ ] ~~Can the scrollable window be an actual image extracted from the PDF?~~
- [x] Be able to view section symbol the same way as paragraph symbols (can discuss)
- [ ] ~~Is there a way to make the PDF open to the page as indicated by the page number within the PDF? Instead of counting page breaks. Issue also pops up with transcript excerpts and condensed versions--the document will have numbered pages, or maybe missing pages, but app counts to the cited page and opens there (when this works).~~

## General bugs
- [x] Refresh and Add Word buttons are sometimes greyed out. Switching to a different case and then switching back fixes it.
- [ ] Add "ignore" or "remove" citation button
- [ ] Add option to remove added word
- [ ] App sometimes behaves differently when performing the same task twice in a row. E.g. opening ITC complaint, connecting it to folder first time gave different results second time.

## Case- or Document-specific bugs:
- [ ] I added two statutes to the folder (9 U.S.C. § 9 and 28 U.S.C. § 1391) and gave them those filenames (i.e. 9 U.S.C. § 9 and 28 U.S.C. § 1391). I then hit “refresh.” The app recognized citations to both documents as 9 U.S.C. § 9. This makes me think that the app is not “reading” the entire filename.

# Seaguard
- [x] Paragraph 9: Ex. A cite opens to Exhibit A within Exhibit A (which is good! - see below). But it’s not clear why this is happening and appears to be random. Opening to the wrong page is a very common error in general.
- [x] Paragraph 20: I made "Final Award" cite to Ex. J using Add Word. Citation reading "Final Award at 31" opens to page 7 of the Exhibit J. But works correctly in next paragraph.

# Terry
- [x] "(See Cole Dep. Ex. 1, attached as Ex. 4.)" - Catches Ex. 1 but not Ex. 4
- [x] Missing Ex. 2, various others throughout doc. E.g. Ex. 4 on Page 11
I tried to force it to recognize the Ex. 4 citation using Add Word. But when i went to add the word, the drop down menu of available files only showed me three documents, not all of the ones in the folder.
- [x] Ex. 10 opened to page 10
- [x] Dkt No 771 is recognized (nice!) but opens to last page of document
- [ ] The cites to pages and lines of transcripts do not work effectively because the transcripts are excerpts, meaning pages are missing. And because they use the “condensed” format of transcripts that puts four pages of transcription on a single page. 
    - If we could “look inside” these transcripts and recognize these things, maybe we could make it work still.

# Feinsod
- [x] Would not recognize exhibit in file if titled "Ex. 1 Feinsod Deposition."
- [x] Only Ex. 1 is in folder. But it recognizes every Ex. in the document as Ex. 1. This is important because there might be times when I only need to see citations to one exhibit, not all of them. I need the program to only recognize the exhibits in the folder.

# ITC complaint
- [ ] Exhibit cites to any exhibit starting with Ex. 2 (e.g. 29) or Ex. 5 (eg. 50) will cite to Ex. 2 or Ex. 5. Also happens with at least some cites starting with Ex. 3 and Ex. 4.
- [ ] Cannot fix with Add Word: I attempted to make cites to Exhibit 40 actually point to Exhibit 40 instead of Exhibit 4 and it did not work.
- [ ] Most exhibits open to wrong specific page after "at"
- [ ] Cites to two places within a single exhibit (e.g. "Ex. 24 at 2-3, 14") do not result in two highlights and two cites. It only highlights the word "Exhibit" once (and then opens to Ex. 2 instead of Ex. 24).
- [ ] "Preview" of paragraph symbol on page 43 not working. Opens up a box, but it's blank and I can type in it.
- [ ] Refresh button did not catch "15 U.S.C. § 1125" citation after adding document with that filename to the folder

# ITC supplement
- [ ] This is an interesting one because the “Supplement” document cites to exhibits found in both the ITC Complaint folder and the ITC Supplement folder. So I experimented with switching back and forth between the two (i.e. pointing the program at the supplement folder and reviewing those citations, then pointing it at the complaint folder and reviewing those).
- [ ] Overall, the program worked much better when looking at the supplement folder; when pointed at the complaint folder, all the bugs noted above reoccurred. 
- [ ] I also experimented with combining the complaint and supplement folders, and then pointing the Supplement document at that folder. It got very buggy again, with many citations to things like Ex. 67, for example, opening up to Ex. 6 (bug mentioned in detail above).
- [ ] There were a few citations to the Complaint that included the paragraph symbol, e.g. “See Compl. ¶ 88.” The scrollable window worked perfectly.


# Changes
- [ ] Exhibits attached to the end of a main document
- [ ] The “front door” option
- [ ] Exhibits within exhibits
