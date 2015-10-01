---
layout: post
title: NuGet Packages Statistics Update
category: blog
---
The Nuget team informed me that they will be increasing the download counts of my NuGet package(s) this week. 

Their old statistics warehouse contained download facts for non-normalized versions, whereas all of their services only take normalized versions into account. The normalized version standardizes the version formats in use and makes querying and comparing packages easier. Say a package has version 2.0.0.0, they normalize that version into 2.0.0 and work with that version number instead. The same goes for 2.0 which becomes 2.0.0, essentially considering 2.0.0.0 and 2.0 as the same version. Another example would be version 1.2.3.0115, which is normalized as 1.2.3.115.

Unfortunately, the old statistics warehouse was never updated when they started normalizing version numbers. The result of this change a few years ago was that the NuGet gallery no longer listed the correct number of package downloads, which they are now fixing.

Over the next few days, they will be making the following changes:

- NLoad 0.1.0 - increase with 18 downloads
- NLoad 0.2.1 - increase with 19 downloads
- NLoad 0.2.2 - increase with 16 downloads
- NLoad 0.2.5 - increase with 17 downloads
- NLoad 0.2.6 - increase with 14 downloads
- NLoad 0.2.7 - increase with 17 downloads
- NLoad 0.3.12 - increase with 11 downloads
- NLoad 0.3.14 - increase with 10 downloads
- NLoad 0.3.17 - increase with 10 downloads
- NLoad 0.3.19 - increase with 16 downloads
- NLoad 0.3.1-alpha - increase with 10 downloads
- NLoad 0.3.3-alpha - increase with 11 downloads
- NLoad 0.3.7 - increase with 17 downloads
- NAnt.Core 0.92.0 - increase with 53 downloads
