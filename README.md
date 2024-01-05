# What

JPG scans of the 1989 BMW Repair Manual for E30 M3 (S14B23) and 320is (S14B20), indexed here via HTML.

# Why

The repair manual is already available online in various formats (VM, PDF, etc.) but I wanted a very simple HTML based 'file explorer' which would work on any mobile phone browser.

(Typically when I want to double check the repair manual, I am underneath the car, covered in oily-sh*te and not in the mood to de-glove, trapse into the house, and scroll through a PDF on a laptop.)

Putting all of these documents on Github gives the E30 M3/320is community an organised image dump, which should hopefully last for a very long time without relying on a single individual custodian.

# Where

My domain (disuye.com) is hosted via Github pages and `./index.html` can be launched from the link below.

[https://disuye.com/E30-M3-320is/](https://disuye.com/E30-M3-320is/)

# Site Structure

`./index.html` = only lists BMW's index pages; click links to open JPGs in a new window; or click section titles to view `/SECTION/index.html`

`./SECTION/index.html` = list of scanned JPGs relevant to indivudal sections ('Engine', 'Brakes' etc. etc.); click links to open JPGs in a new window

`./index-all.hmtl` = list of all scanned JPGs together on one page

`./index-pages.html` = work-in-progress, rapid thumbnail viewer

# JPG Source

Nearly all of the JPG images were blatantly scraped from [https://m3guru.bmwe30m3.net/](https://m3guru.bmwe30m3.net/) which – at the time of coding this repository – seemed to be a defunct website. However, m3guru created a new blog post shortly before Xmas 2023, so I've since reached out to apologise :)

FWIW, I spent quite a bit of time editing the scraped JPGs: Deleted duplicates, re-named files based on image content & sequentially as per the original manual, added missing or poorly scanned pages (work-in-progress; I have multiple versions of the original manual grabbed from the darkest corners of the internet). 

I used WGET for the JPG scrape, no sketchy hacking involved.

# Goals

* Make the BMW E30 M3/320is Repair Manual quickly accessible from any mobile browser.
* Stick to a simple 'file explorer' style design. Nothing fancy.
* Only use simple CSS and HTML.
* Assist anyone else who wants to download this repo; be my guest :)
* OCR/convert BMW's index page JPGs to searchable text/HTML.
* Label all JPG links on the Torque Specs page (as per Torque > Engine section), aka searchable Table of Contents.

# Notes on Copyright

Obviously these images ultimately belong to BMW: If they have any issue then I will delete the entire repo on request. BMW seems to make all of this data freely available from BMW-GroupArchiv.de ... which I guess makes it public domain? 

As for my HTML and CSS, go nuts, do what you want.

# Resources

https://m3guru.bmwe30m3.net/
https://s14net.vbulletin.net/forum/
https://bmw-grouparchiv.de/irc/
