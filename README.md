## 67-272: BookManager 3 ##

This is a lab project for 67-272: Application Design and Development.  The primary objectives of this lab are (1) to teach students how controllers work, and (2) how to work with views and integrate [Foundation](http://foundation.zurb.com/) in their projects.  

In contrast with the first version of BookManager, this project assumes that this is for one publisher (in this case the infamous Acme Publishing, which is the favorite publisher for [Wile E. Coyote](http://decmod.diegoazeta.org/resources/1-Exercises/Acme-Catalog.jpg) and also a producer of great tech books).  In this case, Acme not only wants to track books and authors, but also wants to track books through the various stages of the publishing process: from the initial proposals to signing a contract with author(s) to finally publishing the book.

To set this up, clone this repository, run the `bundle install` command to ensure you have all the needed gems and then create the database with `rake db:migrate`.  If you want to populate the system with fictitious, but somewhat realistic data, you can run the `rake db:populate` command to get 50 authors and 54 books (from 13 categories) in various stages of the publishing process.  Once you start the app in your browser, you can log in with the username 'admin' and the password 'secret' (a very secure combo, of course; no one would ever guess that)

Instructions for how to complete the lab and fill in the missing components can be found in the lab instructions found on the [67-272 course site](http://67272.cmuis.net/labs/7).