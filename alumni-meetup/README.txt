IIT KGP CSE Alumni Meetup, Bengaluru - one page site
=====================================================

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

If the department server has no outbound access for webfonts, the two
<link> tags to fonts.googleapis.com in <head> can be deleted. The page
then falls back to the system sans-serif and still renders correctly.

Things to update before publishing
----------------------------------
1. Registration link: search index.html for "docs.google.com" and
   replace if the form URL changes. It appears twice.
2. "Microcredit Course on AI Innovation" - please confirm whether this
   should read "Microcredential".
3. Confirm the spelling and designation of Anand Deshpande.
4. After the event, the simplest change is to replace the two Register
   buttons with a line of text saying the meetup has concluded.

Contact address used on the page: alumni-connect@cse.iitkgp.ac.in
