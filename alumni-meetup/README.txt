IIT KGP CSE/IT Alumni Meetup, Bengaluru - one page site
========================================================

Files
-----
index.html   the page. Self-contained apart from the assets folder
             and one Google Fonts request.
assets/      banner, three speaker portraits, flyer preview image,
             and the flyer PDF.

How to host
-----------
Copy the whole folder to the web root, for example

    /var/www/html/alumni-meetup/

and it will be served at

    https://cse.iitkgp.ac.in/alumni-meetup/

Keep index.html and the assets folder together. All paths inside
index.html are relative, so the folder can sit anywhere.

If the server has no outbound access for webfonts, delete the two
<link> tags to fonts.googleapis.com in <head>. The page then falls
back to the system sans-serif and still renders correctly.

Things to check before publishing
---------------------------------
1. The flyer PDF in assets/ is the older version. It does not mention
   the Rs 500 fee, and its agenda wording differs from the page.
   Replace it with an updated flyer, or remove the two download links
   in the Register section.
2. Registration link: search index.html for "docs.google.com".
   It appears once.
3. UPI ID on the page: technologyalumniassociationbangalore@sbi
4. Confirm the spelling and designation of Anand Deshpande.
5. After the event, replace the Register button with a line saying
   the meetup has concluded.

Contact address used on the page: alumni-connect@cse.iitkgp.ac.in
