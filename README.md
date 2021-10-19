# chrome-new-tab

This is small project that I did for my self at my current role in Yapily.

I personally do not enjoy the use of bookmarks as they become messy really quickly, so I just designed a quick static page with the most common links I use.

While using it I noticed that in Chrome if you change the landing page for a new tab, the address bar is not focused+highlighted anymore, which made it inconvenient when I just wanted to Google something.  
To resolve this, I just added an input field that redirects to www.google.com and apends a query parameter `q=input` so it searches for it straightaway, then I made the input search bar autofocus on page load.
