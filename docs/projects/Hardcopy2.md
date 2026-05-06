---
tags:
  - libsci
  - compsci
  - research
share: "true"
category: projects
---
I will begin planning with an abstract and go from there. I am interested in a nice book tracking and acquisition system. From my research, nothing handles acquisition in a way that is EZ for a normal user. The best way I have found is Readarr, with Hardcover and Goodreads list imports. However, this has many problems. The first being that Readarr does not support both service imports on the same instance, and Goodreads imports require using Goodreads as the meta source. This isn’t a horrible problem, since I don’t really care for Goodreads. However, the other problem is that list imports suck. The UX for adding books is bad, you can’t add series at once, and you can’t track new releases in a series. The ideal solution would be tracking your Hardcover follows. The UX for following things is good, and you can follow books, series, and authors independently. No existing software does this. Also, using Hardcover as both the tracker and meta source means you always find the correct metadata. Building this system is simple. You could connect this system to any library management system, like CWA or Grimmory. However, I also don’t love existing management solutions. Thinking about it, it may make sense to draft requirements as the first thing. I obviously already have some requirements or I wouldn’t have anything to write about. As much as I want ebook purity, I do enjoy audiobooks, and I want the acquisition process to be similarly EZ. Here is a solution, just make the drop location for ebooks and audiobooks independently configurable. Additionally, could make a simple toggle for each Hardcover account being tracked (ebook-only, audiobook-only, both).
