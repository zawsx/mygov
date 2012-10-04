---
title: "Government Forms just got an Upgrade"
description: "Today Project MyGov is pleased to announce the release of a small, open source tool to improve the experience of completing government (or other) PDF-based forms"
author: "Benjamin Balter and Greg Gershman"
layout: post
comments: true
sharing: true
category: annoucments
tags: code, pdf, forms
published: false

---

As we sat down to reimagine the way citizens interact with government, we quickly realized, that at their most basic level, many citizen services are transacted using standarized forms contained within a file known as a  [PDF](http://en.wikipedia.org/wiki/Portable_Document_Format). PDFs are a popular file format used to represent traditional, paper documents online while preserving their original, off-line formatting. PDFs ensure others cannot make changes to the original document, and as such, serve as a logical container for forms and legal documents to which accuracy is key.

Despite their widespread use, however, PDFs have some limitations. For one, because such files are traditionally downloaded to a user's desktop computer before they are viewed, and thus live outside the user's web browser, it's hard to build web-based tools to improve the experience of completing the forms they contain. Second, because PDFs are digital representations of real-world paper documents, submitting PDFs forms to agencies often requies printing the document and physically mailing it in. In a world where an increasing number of day-to-day tasks are now being completed online — from paying bills to staying in touch with classmates — clearly, such a paper-based process deserves a closer look.

Today we are pleased to announce the release of [a small, open source tool](https://github.com/presidential-innovation-fellows/pdf-filler) to improve the experience of completing government (or other) PDF-based forms. The tool, which we've creatively named "[PDF Filler](https://github.com/presidential-innovation-fellows/pdf-filler)", provides web developers with a standardized ([RESTful](http://en.wikipedia.org/wiki/Representational_state_transfer) in geek speak), interface that, when provided a user's responses, returns the completed form.

So why is this useful? For one, agencies can use this tool to begin embedding existing forms within their website, rather than requiring users to download and complete the PDF offline. Second, because the tool is built using a common standard, other developers can begin to build tools on top of the form, such as, for example, a tool to aggregate and complete common fields like name and address across multiple forms. Finally, as government entities start to use web-based forms to collect information, we will slowly transition to a more future-proof system of interacting with citizens where by data (the information you submit) can remain distint from presentation (the form itself).
