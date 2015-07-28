Steps to reproduce:

1) Install Jekyll 3.0.0.pre.beta8
2) Run jekyll serve
3) You should see the initial page with a single post
4) Create a new post
5) The is processed and corresponding HTML file gets created, Jekyll serves it just fine but it doesn't appear in the listing or RSS feed
6) Stop the Jekyll
7) Run jekyll clean
8) Run jekyll serve again
9) Now the new post appears in the listing as well

Running Jekyll 3.0.0.pre.beta8, Ruby 2.1.5
