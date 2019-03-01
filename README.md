# Bookmark Server

An exercise building a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

From the [HTTP & Web Servers Udacity Course](https://classroom.udacity.com/courses/ud303) and part of my aim to review foundational concepts re: the internet and getting more familiar with Python after five years of working heavily in the weeds of server-side Node.js and C++ development.
