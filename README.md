# GreenGluonCMS
PHP/MySQL Content Management System.

## Technology Used
- PHP
- MySQL
- Google Oauth API
- Google Custom Search Engine (CSE) API
- FPDF

## Big Sample Sites Using This Code
- [EarthFluent.com: Teaching Languages to the World](http://www.earthfluent.com/)

   Provides language lessons and quizzing for English speakers wishing to learn one of 12 available languages.  This uses Chrome-only's voiceSynthesizer to accurately reproduce accent and pronunciation, whether you are studying French or Korean.  Also, Gooogle CSE (Custom Search Engine) is used here, using the image search to generate the images used to identify words in the lessons and quizzes.

- [WordWeight.com: Weighing Your Worlds](http://www.wordweight.com/)

   This site is handling 100,000 different URL queries (i.e., site.com/word/), which then serves up results from a dictionary that was parsed into a MySQL DB.

- [CopyLeftLicense.com: Every Open Source License](http://www.copyleftlicense.com/)

    This site provides a basic way to upload and sort content that may then be liked, commented on, tagged, reposted on 40 different social media networks, downloaded in 18 different formats, listened to using a built-in audio player, and properly crawled by websites using the specifications for sitemap xml files and robots txt files.

## Small Sample Sites Using This Code
- [SortWords.com: Sorting Your Lists of Words For You](http://www.sortwords.com/)
- [ListKeywords.com: Finding and Listing Your Keywords For You](http://www.listkeywords.com/)
- [RemoveBlankLines.com: Removing Blank Lines from Lists](http://www.removeblanklines.com/)
- [RemoveDuplicateLines.com: Removing Duplicate Entries from Lists](http://www.removeduplicatelines.com/)
- [RemoveSpacing.com: Removing Spaces and Spacing from Your Text](http://www.removespacing.com/)

Note: All of the big and small sample sites are running on the exact same codebase.

## Technology Implemented
- All Formats Available : Mobile, PDF, Printer-Friendly, Text, RTF, EPub, DAISY, SGML, JSON, XML, CSV, Latex, OPDS, RDF, and others.  User merely needs to change their given URL's file-extension to get the alternate version.
- Audioplayer for text using Google Chrome's Voice Synthesizer.
- User tagging, liking, commenting system, where users may authenticate through the site's own login.php, or through their gmail account.
- Document Generation Caching with Auto-Invalidation as soon as the content changes.
- SiteMap XML Spec and SiteMap-to-Crawler Curl-Pinging for 500 Search Engines.
- Native, Light-Weight Stats-Tracker.
- Lexical Parsers Capable of Generating Keywords, Definitions, or Facts from Text.
- Autogenerated Share Links for 40 Different Social Media Sites.
- All Base Conversions and Customizable Base Alphabets (Hex, Base64, etc.).
- Internal Server Error Logging and Handling System.
- Number Theory, RSA decrypter/encrypter, and Associated, Cryptology Functions (these functions are not used in security of the code, they are for cryptological research purposes)
- Robots.Txt Autogeneration in TXT, XML, and HTML formats.

## License
Green Gluon CMS is hereby released under the BSD-3-Clause License.

Software being used under the Green Gluon CMS, such as Google OAuth, Google CSE, FPDF, etc., may have its own terms and services outside of the above-given license.  I make no claims on the terms-of-use of source code files appearing here that I did not write.
