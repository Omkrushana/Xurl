# Xurl

# Xurl - URL Shortener Project

Description:
Xurl is a simple URL shortener project that allows users to create shortened versions of long URLs. This project aims to provide a straightforward solution for generating concise and easy-to-share links.

Features:

URL Shortening: Users can input long URLs and receive shortened versions.
Custom Short URLs: Optionally, users can specify custom aliases for their shortened URLs.
QR Code Generation: Xurl generates QR codes for each shortened URL for easy sharing and access.
Analytics: Basic analytics are provided to track the number of clicks on shortened URLs.
Usage:

Shorten a URL:

Input the long URL you want to shorten into the provided field.
Optionally, specify a custom alias for the shortened URL.
Click the "Shorten" button to generate the shortened URL.
Access Shortened URLs:

Simply copy the shortened URL provided after shortening a long URL.
Paste the shortened URL into a web browser to access the original long URL.
QR Code Generation:

Each shortened URL comes with a QR code.
To generate the QR code, simply click on the provided link or scan the QR code image.
Analytics:

Basic analytics are available to track the number of clicks on each shortened URL.
Access analytics by navigating to the provided analytics page.


XURL is a utility that can be used to generate and retrieve short URLs when we don’t want to use the original longer URLs.

During the course of this project,

Created a short url library with required methods.
Implemented register method to take a long URL and return a shorter URL.
Implemented a method to lookup the long URL by providing the short URL.
Implemented hit count to track number of long URL lookups.
Tested this implementation with test cases.
image

XURL Interface

Build XURL from scratch
Scope of Work
Create a concrete class which implements a short URL interface class provided. It contains all the methods that can be used to create long URL to short URL mappings.
Implement a method to take a long URL as input, generate a random 9 character short URL and return it. Also maintain this mapping using a hash map for quick retrieval.
Implement a method to take a long URL and a custom short URL as input and register that mapping. 
Error handling to make sure each long URL maps to only one short URL and vice versa.
Implement a method to lookup short URL for a given long URL, from the mapping created.
Implement a method to delete the mapping based on a long URL.
Implement a counter to keep track of the hit count for each long URL - which tells us how many times a particular long URL has been looked up.
Test these methods using test cases.

Skills used
Core Java, Interfaces, Debugging
