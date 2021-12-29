https://github.com/jdwright58/ETGD
==================================
20211228
Added a header to each page with the Gusher Days symbol and general info
1.In /css/etgd.css added classes:
    .hdr
    .hdr-text
    .hdr-img

2.Each HTML file:
  a.Added <header> and code
  b.Added <nav> around <ul>
  c.Commented gusher days image in <div>
==================================
20211225
1.In /css/footer.html: made absolute reference to etgd.css

2.In /css/reset.css: commented lines 69-76 that was adding space between my <mark> lines

3.Each HTML file:
  a.Add stylesheet /css/reset.css
  b.Change footer src to /iframes folder
  c.Removed /footer.html (now referenced in folder /iframes)

4./css/etgd.css: added classes 
  a).board-head
  b).board-table
  c).board-member-left
  d).board-member-right
===============================
20211224
Each html file: 
  Change to absolute site folders
    <link rel="icon" 
    <link rel="stylesheet" 
    <body style="background-image:
    <li><a href="index.html
    ...
    <img class="etgd" src=
    application links
    <iframe src="footer.html
  Removed commented code in index.html related to add-to-my-calendar
====================================
20211208
etgd.css
  Added body height 100vh
  Changed footer position to sticky
  Changed footer top: 100vh
===================================
20211205
CSS
  Created css folder
  Copied css files
  Updated <head> sections of all HTML
  Deleted original root css files.
basstournament.html
  Added 2022 to the tournament text
  Added the Gusher Days logo as a list item in the topnav, just an item with an image but no action.
  Turned the div into a grid with one empty item and one with the text in it.