
barcodes
======

DEMO: <a href="https://martbhell.github.io/barcodes/"> https://martbhell.github.io/barcodes/ </a>

Takes some input in form of a csv file then prints some pay forms with bar codes 


Put the index.html somewhere and point your browser to it :)

Dependencies
============

              -   https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js
              -   https://cdnjs.cloudflare.com/ajax/libs/PapaParse/4.3.7/papaparse.min.js
              -   https://unpkg.com/finnish-bank-utils@1.3.3/dist/finnish-bank-utils.js
              -   https://cdn.jsdelivr.net/jsbarcode/3.6.0/JsBarcode.all.min.js

Known Issues
============

   - Input page looks like it's from 1995. PRs are most welcome
   - No page splitting for nice printing. 
     - In google-chrome on Windows 10 with default margins one needs to scale it down to 86 or so to make it look nice in preview
   - Virtual Bar codes must have a valid reference number
