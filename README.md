This repository contains all the files for assignment 3.
The corpus of data scraped from the website https://goodreads.com. This data consists of three books. These books were chosen based on my favorite books and books that I still want to read. The following data 
was scraped: the author, date of publication, number of pages and the summary of each book. The csv file consists of this scraped data. As the text on the website was already relatively clean, very
little clean up was necessary. The name of author appears twice, as I was not able to scrape the name only once, due to the way the html code was set up, nor was I able to create a csv file in Jupyter Python. 
The Jypiter notebook consists of codes used to scrape the data of the author, date of publication, number of pages and the summary for each book. For the terms and conditions, the following was described:

See http://www.robotstxt.org/robotstxt.html for documentation on how to use the robots.txt file
User-agent: EtaoSpider
Disallow: /

User-agent: GPTBot
Disallow: /

User-agent: CCBot
Disallow: /

User-agent: facebookexternalhit
Allow: /user/year_in_books

User-agent: Mediapartners-Google
Disallow: /about/team_member/
Disallow: /admin
Disallow: /api
Disallow: /blog/list_rss
Disallow: /book/reviews/
Disallow: /book_link/follow/
Disallow: /buy_buttons/
Disallow: /ebooks
Disallow: /friend/add_as_friend
Disallow: /home/index_rss
Disallow: /oggiPlayerLoader.htm
Disallow: /photo/group/
Disallow: /quotes/list_rss
Disallow: /review/list
Disallow: /review/list_rss
Disallow: /review/rate
Disallow: /shelf/user_shelves
Disallow: /tooltips
Disallow: /track
Disallow: /trivia/answer
Disallow: /user/updates_rss
Disallow: /*reviewFilters

User-agent: *
Allow: /work/editions
Allow: /work/quotes
Disallow: /about/team_member/
Disallow: /admin
Disallow: /api
Disallow: /blog/list_rss
Disallow: /book/reviews/
Disallow: /book_link/follow/
Disallow: /buy_buttons/
Disallow: /ebooks
Disallow: /friend/add_as_friend
Disallow: /home/index_rss
Disallow: /oggiPlayerLoader.htm
Disallow: /photo/group/
Disallow: /quotes/list_rss
Disallow: /quotes/tag
Disallow: /review/list
Disallow: /review/list_rss
Disallow: /review/rate
Disallow: /review/show
Disallow: /search
Disallow: /shelf/user_shelves
Disallow: /tooltips
Disallow: /track
Disallow: /trivia/answer
Disallow: /user/updates_rss
Disallow: /user/year_in_books
Disallow: /videos/
Disallow: /work
Disallow: /*reviewFilters

Sitemap: https://www.goodreads.com/siteindex.author.xml
Sitemap: https://www.goodreads.com/siteindex.author_community_question.xml
Sitemap: https://www.goodreads.com/siteindex.award.xml
Sitemap: https://www.goodreads.com/siteindex.blog.xml
Sitemap: https://www.goodreads.com/siteindex.book_community_question.xml
Sitemap: https://www.goodreads.com/siteindex.genre.xml
Sitemap: https://www.goodreads.com/siteindex.giveaway.xml
Sitemap: https://www.goodreads.com/siteindex.group.xml
Sitemap: https://www.goodreads.com/siteindex.index.xml
Sitemap: https://www.goodreads.com/siteindex.interview.xml
Sitemap: https://www.goodreads.com/siteindex.list.xml
Sitemap: https://www.goodreads.com/siteindex.quote.xml
Sitemap: https://www.goodreads.com/siteindex.quote_tag.xml
Sitemap: https://www.goodreads.com/siteindex.related_work.xml
Sitemap: https://www.goodreads.com/siteindex.topic.xml
Sitemap: https://www.goodreads.com/siteindex.user.xml

the page I used, goodreads.com/book/- means that I was allowed to scrape this as it was not disallowed. 
