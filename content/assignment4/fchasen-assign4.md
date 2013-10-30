Title: Governance of PDF.js
Date: 2013-10-29 10:00
Category: assignment4
Slug: fchasen-assign4
Tags: pdfjs
Author: Fred Chasen
Summary: A overview of governance in the PDF.js project and update on my contributions progress. 

### Weekly Meetings
Most discussions about important decisions seem to take place in the weekly meetings. Theses are conference calls between the core developers, though they are open to public. Notes of the meeting are taken and put up on (etherpad)[https://etherpad.mozilla.org/pdfjs-2012-04-19] or sent to the (group list)[https://groups.google.com/forum/#!searchin/mozilla.dev.pdf-js/project$20meeting$20notes]. 

Though its possible there are back-channel discussions outside of these meetings, the notes indicate they take place in the weekly meetings. For instance the (notes)[https://groups.google.com/forum/#!searchin/mozilla.dev.pdf-js/project$20meeting$20notes/mozilla.dev.pdf-js/mygtw077chk/PXc8mqwdJuYJ] of a meeting in 2011 are broken down into Goals, Decisions and Discussion.

While there are many notes publicly available on etherpad, to view them you need know the date or url of the meeting. There is no way to search them or view them as a list. This makes seeing a history of discussion much more difficult then if the mailing list was used.

### Consensus 

As part of Mozilla, pdf.js has several employees working on it, including a manager. The manager seems to be the one taking the notes on the meetings but it appears that most decisions are made by consensus. In a (thread)[https://groups.google.com/forum/#!searchin/mozilla.dev.pdf-js/vote/mozilla.dev.pdf-js/yx644WT4X6M/UDybOESvx5cJ] about changing the namespace from PDFJS to something lowercased 3 lead developers weighed in, ending with a vote to keep it the way it was.

Technical issue are often voted on in github issue. In an (issue)[https://github.com/mozilla/pdf.js/issues/80] the choice between using “null” or “undefined” is resolved by a simple vote. Another (issue)[https://github.com/mozilla/pdf.js/pull/780] has a longer discussion about what to name a button and what icon is should have. Different developers chime in with name suggestions for the button before deciding to close the issue.

### My Contributions Progress

The (issue I am working on)[https://github.com/mozilla/pdf.js/pull/3815] is currently in the process of being reviewed, and might end up needing a longer discussion. The feature I added causes the top toolbar to slide in and out automatically when a parameter is set. Making this nicely adjust the rest of the UI ends up hooking into many different places of the code. As a newcomer I was unaware of all the features it affected. Thankfully other contributors have been reviewing my code and pointing out all the UI elements I missed.

I think the functionality is complete now, however getting everything to work required quite a bit of code. As this sliding is a pretty trivial feature that not many people will run into, there might have to be a decision about if it worth adding at all or if the functionality might fit in better somewhere else. 