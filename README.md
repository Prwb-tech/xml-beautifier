# XML Beautifier: free Chrome extension

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-Install%20free-brightgreen)](https://chromewebstore.google.com/)
[![Works Offline](https://img.shields.io/badge/Works-Offline-blue)]()
[![No Upload](https://img.shields.io/badge/No%20Upload-Local%20Processing-lightgrey)]()

An XML file landed on your computer: an export, a log, a price list from a supplier. Double-click does nothing, Notepad shows one endless line, and your eyes give up around line two. You don't need to install anything: view and beautify it right in your browser, and keep the file exactly where it is.

## What it does

XML Beautifier opens XML files offline, and the viewer takes whatever you have: paste the text, drop a file, open xml files from disk with the **Open file** button, or hit **Try a sample** before your own file shows up. Four ways in, zero setup: pick one and beautify.

**Beautify** is the main move: proper indentation, one node per line (pretty print xml under a friendlier name). Messy input in, formatted tree out; a file that arrived as one endless line becomes something you can actually read.

The view side earns its keep on big files: in the xml viewer, **syntax highlighting** makes tags and values distinguishable at a glance, and **collapsible nodes** fold the branches you don't care about. A file five thousand lines long stops being scary once half of it is folded away.

**Minify** does the opposite of Beautify: it strips whitespace and formatting back out when the XML needs to travel light (same data, fewer bytes). And when a file is broken, the extension **pinpoints the exact error line**, so you fix the file instead of guessing at it.

**What it doesn't do, honestly.** It doesn't edit XML: this is a read-and-tidy tool, not an editor. It doesn't validate against XSD schemas: the pinpointed error in broken XML covers the everyday xml validator need, not the schema-level one. And it doesn't replace an IDE: it isn't trying to be a development environment, and you'd notice if it pretended. For everything short of that (look, tidy, share a readable version), it's enough.


## Who it's for

A developer with a config export, an analyst with a service log, and the quiet majority whose story is "the supplier sent a price list in XML and I need to read it". None of them wants an IDE for this. The job is smaller: **view xml file contents** without installing anything, and **beautify xml** into something a human can scan before the meeting starts. Export, log or price list, the routine is the same: open, look, breathe out.


## Quick start

1. Install XML Beautifier from the [Chrome Web Store](https://chromewebstore.google.com/detail/xml-beautifier/kmmhbckcibgpppnlhlkbkhpcahjbjpnn) (free, one click).
2. Paste, drop or open the file: formatted view instantly.

There is nothing between step two and done: no account, no settings, no import dialog. The viewer just shows the file, formatted from the first second. Hit **Try a sample** if your file hasn't arrived yet and you want to see the shape of the thing before yours lands.


## Questions and answers

### How to beautify an XML file?

Paste it into the extension and press **Beautify**: the xml viewer indents the tree, and the formatted result reads like a careful person wrote it. If the XML lives on a web page, select it there and run **Beautify selected XML** from the right-click menu. People who want to **beautify xml online** usually land on converter sites; this does the same job with the file never leaving your machine. The whole loop is two clicks: paste, Beautify, read.

### How to format XML without installing software?

The typical search ends at an xml formatter website that asks for the file to be uploaded first. The offline route is simpler: install the extension once, and from then on you **format xml** by pasting, dropping or opening the file in the viewer. It works offline (behind firewalls, on locked-down machines, on a train), and nothing is uploaded in the process. The file stays where it landed; only the view changes.

### Is XML Beautifier safe for my data?

Yes: there is no server in the story. XML Beautifier parses the file inside your browser: nothing is uploaded, nothing is sent, and no account exists to attach your data to. Logs and price lists feel private because they are; this treats them that way by architecture, not by policy: there is nothing that could send anything anywhere.


## Privacy

Nothing leaves your browser. The XML is parsed locally, inside the viewer: no server to upload to, no account to log into, no copy of your file anywhere but your machine. That's architecture, not a policy; the privacy story is short because the data flow is short. Logs, exports and supplier price lists stay exactly where they arrived.


## Links

- **[Install — Chrome Web Store](https://chromewebstore.google.com/detail/xml-beautifier/kmmhbckcibgpppnlhlkbkhpcahjbjpnn)** — free, one click.
- **[Privacy](https://pinwisp.com/xml-beautifier/privacy)** — privacy policy.
- **[More free tools](https://pinwisp.com)** — other small and honest utilities from the same bench.
