# What

JPG scans of the 1989 BMW Repair Manual for E30 M3 (S14B23) and 320is (S14B20), indexed here via HTML.

# Why

The repair manual is already available online in various formats (VM, PDF, etc.) but I wanted a very simple HTML based 'file explorer' which would work on any mobile phone browser.

(Typically when I want to double check the repair manual, I am underneath the car, covered in oily-sh*te and not in the mood to de-glove, trapse into the house, and scroll through a PDF on a laptop.)

Putting all of these documents on Github gives the E30 M3/320is community an organised image dump, which should hopefully last for a long time without reliance on a single individual custodian.

# Where

My domain (disuye.com) is hosted via Github pages and `./index.html` of this repo can be launched from the link below. Bookmark this GitHub repo should the domain name change.

[https://disuye.com/E30-M3-320is/](https://disuye.com/E30-M3-320is/)

# Site Structure
```
./ index.html
     │
     ├──./ index-all.html ──▻ *.jpg
     ┊       │
     ├───────┘
     │
     ├──./ 00 - Maintenance / index.html  ──▻ *.jpg
     │                           │
     │       ┌───────────────────┘
     │       ├──../ M3-techspec.html
     │       ├──../ 320is-techspec.html
     │       └──../ Reference Images / Bosch Motronic system drawing.png
     │
     ├──./ 00 - Torque Specs / index.hml ──▻ *.jpg 
     ├──./ 11 - Engine / index.html ──▻ *.jpg
     ├──./ 12 - Engine Electrical System / index.html ──▻ *.jpg
     │
     ├──./ 1990 BMW M3 Electrical Troubleshooting Manual / index.html ──▻ *.jpg
     │
     ├──./ 13 - Fuel System / index.html ──▻ *.jpg
     ├──./ 16 - Fuel Tank and Lines / index.html ──▻ *.jpg
     ├──./ 17 - Radiator / index.html ──▻ *.jpg
     ├──./ 18 - Exhaust System / index.html ──▻ *.jpg
     ├──./ 21 - Clutch / index.html ──▻ *.jpg
     ├──./ 23 - Manual Transmission / index.html ──▻ *.jpg
     ├──./ 25 - Gear Shift Mechanism / index.html ──▻ *.jpg
     ├──./ 26 - Propellor Shaft / index.html ──▻ *.jpg
     ├──./ 31 - Front Axle / index.html ──▻ *.jpg
     ├──./ 33 - Rear Axle / index.html ──▻ *.jpg
     ├──./ 34 - Brakes / index.html ──▻ *.jpg
     ├──./ 35 - Pedals / index.html ──▻ *.jpg
     ├──./ 36 - Wheels and Tires / index.html ──▻ *.jpg
     ├──./ 41 - Body / index.html ──▻ *.jpg
     ├──./ 41 - Body (Convertibles) / index.html ──▻ *.jpg
     ├──./ 51 - Body Equipment / index.html ──▻ *.jpg
     ├──./ 52 - Seats / index.html ──▻ *.jpg
     ├──./ 54 - Hood, Sun Roof / index.html ──▻ *.jpg
     ├──./ 62 - Instruments / index.html ──▻ *.jpg
     ├──./ 63 - Lights / index.html ──▻ *.jpg
     ├──./ 64 - Heating and Air Conditioning / index.html ──▻ *.jpg
     ├──./ 65 - Radio and Special Equipment / index.html ──▻ *.jpg
     ├──./ 72 - Equipment and Accessories for Body / index.html ──▻ *.jpg
     └──./ 97 - Body Cavity Sealing and Undercoating / index.html ──▻ *.jpg
```




`./index.html` 

⇧ only lists BMW's index pages; click links to open JPGs in a new window; or click section titles to view `/SECTION/index.html`

`./SECTION/index.html` 

⇧ list of scanned JPGs relevant to indivudal sections ('Engine', 'Brakes' etc. etc.); click links to open JPGs in a new window

`./index-all.hmtl` 

⇧ list of all scanned JPGs together on one page

`./index-pages.html`

⇧ do not look at this, worse-than-beta; CSS-only rapid thumbnail viewer

# JPG Source

Nearly all of the JPG images were blatantly scraped from [https://m3guru.bmwe30m3.net/](https://m3guru.bmwe30m3.net/) which – at the time of coding this repository – seemed to be a defunct website. However, m3guru created a new blog post shortly before Xmas 2023, so I've since reached out to apologise :)

FWIW, I took time editing the scraped JPGs: Deleted duplicates, re-named files based on image content, re-named files sequentially as per the original manual, added missing pages, sections, or included better quality scanned pages from other sources (work-in-progress). 

I used WGET to scrape publicly visible JPGs, so there was no sketchy hacking involved.

And regarding the 1990 BMW M3 Electrical Troubleshooting Manual, that was ripped from PDF to JPG using Affinity Designer, with some adjustments during the batch process.

# Goals

* Make the BMW E30 M3/320is Repair Manual quickly accessible from any mobile browser.
* Stick to a simple 'file explorer' style design. Nothing fancy.
* Stick to simple CSS and HTML. No JS or serverside nonsense.
* Assist anyone else who wants to expand on this repo; be my guest :)
* Convert BMW's index page JPGs to searchable text/HTML.

# Notes on Copyright

Obviously these images ultimately belong to BMW. If BMW takes issue then I will delete the entire repo immediately on request. BMW makes all of this data freely available from BMW-GroupArchiv.de ... there is no fee/cost to download the original PDF. My only intention is to make a 1000++ page PDF file easier to manage on a mobile device. 

Regarding my HTML/CSS – go nuts – do what you want (as long as you don't make any income from it).

# Resources

* https://bmw-grouparchiv.de/irc/
* https://bmw-grouparchiv.de/irc/resultlist/detailpage?id=6336013 <- M3
* https://bmw-grouparchiv.de/irc/resultlist/detailpage?id=3833378 <- 320is

# Other Useful Links

* https://s14net.vbulletin.net/forum/
* https://www.realoem.com/bmw/enUS/select?product=P&archive=1&series=E30
* https://www.hubauer-shop.de/en/carparts/classic/3-classic/ac95-e30-s14/
* https://www.bmwe21.net/?page_id=173 <- 320is
* https://bmwmregistry.com/model_faq.php?id=10 <- 320is
* https://www.e30zone.net/e30wiki/index.php/320iS <- 320is
* https://m3guru.bmwe30m3.net/

# S14 Repair Guides

* https://www.e30sport.net/maintenance/valve_adjustment/valve_adjustment.htm

---

# To Do List

- 00 - &#x2713;
- 11 - &#x2713;
- 12 - &#x2713;
- 13 - &#x2713;
- 14 - &#x2713;
- 17 - &#x2713;
- 18 - &#x2713;
- 21 - &#x2713;
- 23 - &#x2713;
- 25 - &#x2713;
- 26 - &#x2713;
- 31 - &#x2713;
- 33 - &#x2713;
- 34 - &#x2713;
- 36 - &#x2713;
- 41 - Body
- 41 - Body (Convertible)
- 51 - &#x2713;
- 52 - &#x2713;
- 54 - &#x2713;
- 62 - &#x2713;
- 63 - &#x2713;
- 64 - &#x2713;
- 65 - &#x2713; 
- 72 - &#x2713;
- 97 - &#x2713;
