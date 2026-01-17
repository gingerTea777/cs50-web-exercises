#CS50W Project 0: Google Search Implementation
This project is a front-end replica of Google Search, designed to handle user queries and redirect them to live Google results using specific GET parameters.

Core Functionalities
1. Main Search (index.html)
Standard Search: Accepts a query via the q parameter and redirects to Google's search results page.

"I'm Feeling Lucky": Uses the btnI parameter to bypass the results page and navigate directly to the first search result.

Global Navigation: Fixed links in the upper-right corner for seamless switching between Search, Images, and Advanced Search.

2. Image Search (Google_Image_Search.html)
Visual Queries: Dedicated interface for image-specific results.

Hidden Logic: Implements a hidden tbm=isch parameter to ensure Google processes the request specifically through its image database.

3. Advanced Search (Google_Advanced_Search.html)
Filtered Results: Provides four distinct input fields to refine search results:

All these words: (as_q)

Exact word or phrase: (as_epq)

Any of these words: (as_oq)

None of these words: (as_eq)

Formatted Submission: Consolidates multiple inputs into a single Advanced Search query string.

UI Design
Search Interface: Centered layout with a rounded search bar and hover-responsive shadows.

Thematic Alignment: Mimics Google's typography and color palette, specifically the signature blue "Advanced Search" button.

How to test it:
Open index.html.

Enter a query like "Harvard" and click Google Search.

Verify the URL includes ?q=Harvard.

Switch to Advanced Search and test the "None of these words" field to see how it appends - to your search terms.
