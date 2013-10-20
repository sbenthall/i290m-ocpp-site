Title: Contributing to PDF.js
Date: 2013-10-17 10:00
Category: assignment3
Slug: fchasen-assign3
Tags: pdfjs
Author: Fred Chasen
Summary: Automated vs Peer review of contributions to PDF.js

### Contributing and Workflow

The Github wiki of PDF.js has a [Contributing / Workflow](https://github.com/mozilla/pdf.js/wiki/Contributing) guide follow when submitting to the the repository. As a new committer this page was reassuring, as I didn’t have to dig around or ask questions about the norms of the community. By following the steps in the workflow, there should have been no reasons to reject my pull request. 

That document includes links to a code style guide, a “linter” and steps to download and run tests. I reviewed the style guide and started working on [one of the bugs](https://github.com/mozilla/pdf.js/pull/3815) that was marked as for beginners. It took much longer than I expected to finish, as I had to get up to speed with where everything went. 

### Automated Review

Once I was ready to start the process of submitting my changes, I referred back to the workflow document. The first step was to run the lint tool. This tool checks that the code I contributed conforms to the style guide. On the first run, I got many errors but all of them were quick fixes. 

Confident that the code style was good shape, I ran the suite of tests that PDF.js provides to make sure my changes didn’t break anything. As a beginner bug, my contribution didn’t make any major changes so I was confident it the test would pass. Strangely, the tests continually failed on two of the checks. After testing on a version of PDF.js without my changes, I discovered the failures were caused by two corrupted PDFs. My first contribution to the community ended up being the [issue I created](https://github.com/mozilla/pdf.js/issues/3814) for this. The cause of the corruption turned out to be due to the government shutdown. NIH was serving a shutdown page instead of the PDF the test was requesting.

### Peer Review

With the test passing, I created a [pull request](https://github.com/mozilla/pdf.js/pull/3815) with my code. It was quickly reviewed (in the middle of the night) by a contributor from Stockholm, Sweden. The reviewer found several places where my code was inconsistent with the style guide. These should have been obvious to me. I relied too much on the automated linter, when I should have read over the style guide again. He also has several good suggestions to tidy up the code that only a human reviewer could give. 

The reviewer is a frequent contributor, but is newer to the project and had started working on the bug I was fixing 9 months ago. I’m very appreciative of his input and his tone seemed constructive and was neither condescending or overly critical. I’m working on the fixes he proposed and hopefully will have a successfully commit soon.

Two days ago I would have written this update singing the praises of the automated processes PDF.js to assist with code review. After submitting my first pull request I realize they aren’t the magic solutions I first thought they were, though their help to reassure me I wasn’t too far off the code style or breaking anything with my code was invaluable.