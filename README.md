# PISCES (Working Name)
Personal Infograph Search Compute/Control Engine Solution
Alternative name: IAK - I Already Know

*Problem*: We already have good data that solves questions we have. It is sitting in our email, Nextcloud, RSS feed, Pocket, Evernote, Browser history, Reddit subs or other sources that search engines (i.e. Google) cannot see nor prioritize as being a validated/quality source of data for our search enquires.

*Proposed Solution*: Build a Personal (self-hosted?) extendible (i.e. plugins) search engine we can feel safe giving access to our personal data to so it can index, and leverage that as the preferred source of our search results. Data could be our RSS feeds, Pocket saves, Cloud Storage (file or object eg Evernote, Wallaby), social media feeds/graph, stored files, browser history etc - the more you like, save or accumalate, the more the search engine will have to leverage that data to produce relevant results, so if you are a Python fan, but not a Monty Python fan, you will see the stuff you have already (implicitly) vetted as being a good source of Python data. Subscribe to the Python related sub-reddits, or discusion groups but not Java? Search for 'How to do initialize and array?', and only see relevant results for you from sources you trust and value, including that article you saved to Pocket 3 months ago and forgot you thought could come in handy.

*Long Term Possibility*: Build a federated network of personal search engines that share public data indexes (i.e. websites, rss feeds, etc) to discover new sources, plus reduce the need for hundreds of personal search engines to crawl the same data, e.g. pisces.github.com would be seen as the authoritative indexer of (public) GitHub, allowing pre-indexed data to be included without the need to crawl the site, and that guy who is a guru in Python may have the best sources of info for Python docs and tutorials, so why not leverage that accumilate knowledge base?

Proof of Concept Build Targets;
 - System Architecure
 - Security, Privacy and Identity/Access 
 - Data Models
 - Meta, Markdown Language
 - Query Language & boolean logic
 - Query Interface (CLI?)
 - Native Data Formats: PDF, Plain Text, HTML, +?
 - Plugins: IMAP, Pocket, Evernote, Local File Store, WebDAV?, +?
