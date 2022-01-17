https://github.com/jdwright58/ETGD
==================================
Created VendorMap.pdf from spreadsheet.
Added link to the navigation bar on each html page
==================================
20220115
etgd.css
  1.For the Health page
    a.Changed class .body_health to add a double background-image of the color Gusher Days symbol to break up the all blue backgound 
    b.Changed class .container_health to set a max width, left right margin, and a top margin to move off the top of the page.
  2.For the Facebook page
    a.Changed class .body_fb to add a double background-image of the color Gusher Days symbol to break up the all blue backgound
  3.For the Board page
    a.Changed class .body_bpard to add a double background-image of the color Gusher Days symbol to break up the all blue backgound
==================================
20220113
1.Added to all html files
  a.<html lang="en">
  b.<head>
      <meta charset="UTF-8">
      <meta name="description" content="Gusher Days Event Info">
      <meta name="keywords" content="Gusher Days, East Texas Gusher Days", Gladewater Gusher Days>
      <meta name="author" content="Jeff Wright">
==================================
20211231-20220113
1. artscraftscomm.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_ac"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav>commented out menu item for Old Site
  f.<div>changed booth list <div> container to class="container_ac" and <ul>
  g.Moved style settings to test.css
  h.set body_ac <p> font size to 1.25rem
  
2.basstournament.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_bass"
  c.<header> changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>removed grid, set <div> to class="body_bass" with width 40% and margin-left auto, added <h1> for first line, <h2> for the second line.
  g.set body_bass <p> font size to 1.25rem

3.board.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>set background color in class="body_board"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<table>kept <h2> around table because <h2> resizes with browser size changes
  
4.carnival.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_carnival"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>changed attractions list <div> container to class="container_carnival" with items as <ul> font size 2 rem
  
5.carshow.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_carshow"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>set to class="body_carshow" with width 30% and margin-left margin-right auto

6.chilicookoff.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_chili"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>divided into header, rules_left and rules_right.  Set rules as 2 unordered lists.

7.dirtyneckjessies.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_dnj"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>set to class="container_dnj" with max-width = max-content and margin-right auto
 
 8.fb.html 
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>set background color in class="body_fb"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>set to class="container_fb"
  
9.food.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_food"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>set to class="container_food" with max-width = max-content and margin-left auto
  g.Added <h1>Gusher Days Food to the top of <div>

10.health.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>set background color in class="body_health"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav> commented out menu item for Old Site
  f.<div>set to class="container_index" with max-width = max-content and margin-left auto

11.index.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_index"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<nav>commented out menu item for Old Site
  f.<div>styled div for countdown timer, main content, add-to-calendar
  g.<div>removed a div layer around add-to-calendar

12.streetdance.html
  a.<head>tested uncommenting reset.css by adding test.css
  b.<body>moved background image url to class="body_streetdance"
  c.<header>changed  to <header class="hdr"> and removed extra <div>
  d.<header>Changed from both lines h1 to h1 for line 1, h2 for line 2
  e.<div>styled div for main content

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
  c.Commented gusher days image in <div>:
  <img class="etgd" src="/photos/etgd_bw.JPG" alt="East Texas Gusher Days">
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