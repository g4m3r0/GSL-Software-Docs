# ⚙ Changelog

### Version 3.3.0 (11-08-2022)

* \[IMPROVE] Proxy Testing
* \[IMPROVE] Source Scraping
* \[IMPROVE] General performance improvement
* \[IMPROVE] Proxy Judge
* \[FIX] GUI bugs
* \[FIX] Major bugs
* \[FIX] GUI bugs
* \[FIX] Minor bugs
* \[FIX] GUI bugs
* \[FIX] Minor bugs
* \[FIX] Minor bugs

### Version 3.2.1 (24-08-2022)

* \[FIX] GUI bugs
* \[FIX] Minor bugs

### Version 3.2.0 (24-05-2022)

* \[ADD] Export proxies in Scrapebox/Traffic Buddy format
* \[ADD] Busyindicators
* \[ADD] Update StopForumSpam DB feature
* \[IMPROVE] Proxy Testing
* \[IMPROVE] Source Scraping
* \[IMPROVE] General performance improvement
* \[IMPROVE] Proxy Source
* \[IMPROVE] License activation
* \[IMPROVE] Calculate source quality function
* \[FIX] GUI bugs
* \[FIX] Major bugs
* \[FIX] Minor bugs

### Version 3.1.1 (19-03-2022)

* \[IMPROVE] Multi-threading
* \[IMPROVE] Proxy Testing&#x20;
* \[IMPROVE] Proxy Judge&#x20;
* \[FIX] Minor bug

### Version 3.1.0 (19-01-2022)

* \[IMPROVE] Multi-threading
* \[IMPROVE] Proxy Testing
* \[IMPROVE] Socket-based requests
* \[IMPROVE] Performance & resource usage (heavily reducing CPU usage)
* \[IMPROVE] Autopilot function (Download Source when missing)
* \[IMPROVE] Upgrade to .Net 6
* \[IMPROVE] Documentation
* \[FIX] GUI
* \[FIX] Minor bugs

### Version 3.0.6 (13-11-2021)

* \[UPDATED] Proxy-judges
* \[FIXED] Minor Bug

### Version 3.0.5 (07-06-2021)

* \[IMPROVED] DB loading/saving performance
* \[IMPROVED] CPU/RAM usage
* \[FIXED] Bug caused the autopilot and/or proxy test to get stuck
* \[FIXED] Negative values in proxy list status
* \[FIXED] Bug on changing user-agents

In order to speed up the loading and saving time by a factor of 100x of the proxy database we have updated the database structure. That results in the incompatibility of proxy, source and task databases used in the version 3.0.4 and below. Please export your proxy and source list as text file and import them back in after the update.

### Version 3.0.4 (04-06-2021)

* \[IMPROVED] Scrape & Test Feature (Autopilot)
* \[IMPROVED] Proxy testing
* \[IMPROVED] Google Pass Test
* \[IMPROVED] GEO DB
* \[IMPROVED] Blocked IP DB
* \[IMPROVED] GUI
* \[IMPROVED] Error logging/tracking
* \[IMPROVED] Thread scheduler
* \[FIXED] IP blocked by license server
* \[FIXED] Major Bug on testing proxies
* \[FIXED] Bug on changing user-agents

### Version 3.0.3 (02-06-2021)

* \[IMPROVED] Scrape & Test Feature (Autopilot)
* \[IMPROVED] Overall Performance
* \[IMPROVED] Google Pass Test
* \[IMPROVED] GUI
* \[FIXED] Major & Minor Bugs
* \[FIXED] Bug within Google Pass Test

### Version 3.0.2 (21-01-2021)

* \[IMPROVED] Proxy Up/Down count to list
* \[IMPROVED] Proxy Scraping
* \[IMPROVED] Overall Performance
* \[IMPROVED] Google Pass Test
* \[FIXED] Possible deadlock
* \[FIXED] Settings file not accessible
* \[FIXED] Source List not shown correctly
* \[FIXED] Socks4 filter on tasks

### Version 3.0.1 (18-01-2021)

* \[ADDED] Test & Scrape feature
* \[ADDED] Socks4 Support
* \[ADDED] Tips
* \[IMPROVED] Proxy Testing
* \[IMPROVED] Socks5 Support
* \[IMPROVED] GUI
* \[FIXED] Memory Leak on scraping
* \[FIXED] Bug on Google test

### Beta Version 3.0.0 (28-12-2020)

* \[ADDED] Socks5 Support
* \[ADDED] Icons
* \[ADDED] Theme support
* \[IMPROVED] Proxy Testing
* \[IMPROVED] Proxy Scraping
* \[IMPROVED] Save/Load Database
* \[IMPROVED] List statistics
* \[IMPROVED] GUI
* \[IMPROVED] Tasks
* \[FIXED] Memory Leak
* \[FIXED] Minor Bugs
* \[FIXED] Sub-Tasks
* \[REMOVED] Statistic charts
* \[REMOVED] Trial Version

### Version 2.1.1.2 (10-10-2020)

* \[HOTFIX] Threads not stopping correctly
* \[HOTFIX] Error not written to file
* \[HOTFIX] Updater not working properly
* \[FIX] Installer not working on some hypervisors

### Version 2.1.1.1 (18-05-2020)

* \[IMPROVED] Performance
* \[IMPROVED] Proxy Source
* \[FIXED] Memory Leak

### Version 2.1.1.0 (23-04-2020)

* \[IMPROVED] Performance
* \[IMPROVED] Test Performance
* \[IMPROVED] Custom Server API (experimental)
* \[FIXED] Minor Bug Fixes
* \[FIXED] Potential Crash Issue
* \[REMOVED] Trial Support
* \[REMOVED] Statistics

### Version 2.1.0.1 (22-03-2020)

* \[ADDED] Custom Server API (experimental)
* \[IMPROVED] Internal improvements
* \[FIX] Minor Bug Fixes

### Version 2.1.0.0 (22-08-2019)

* \[ADDED] LicenseSpring License System
* \[ADDED] Client/Server API
* \[IMPROVED] Internal improvements
* \[FIXED] Potential Crash Source

### Version 2.0.4.0 (18-01-2018)

* \[IMPROVED] Internal improvements
* \[FIXED] Memory Leak

### Version 2.0.3.1 (17-05-2017)

* \[IMPROVED] Many internal improvements
* \[FIXED] False positive
* \[UPDATED] Testing algorithm
* \[UPDATED] Application Updater

### Version 2.0.3.0 (03-03-2017)

* \[FIXED] Bug with Logfiles
* \[FIXED] Critical Bug & Minor Bugs
* \[ADDED] Button to manually update blocked ip database
* \[ADDED] Ability to use public or your own judge servers
* \[ADDED] Ability to create Sub-Tasks (Tasks that will be executed after the selected Task has been finished)
* \[ADDED] More Export functions in Tasks
* \[IMPROVED] Tasks overall
* \[UPDATED] IP-Country DB
* \[UPDATED] Blocked IP DB
* \[FIXED] Minor Bugs
* \[FIXED] Critical Bug in Settings load/save function
* \[ADDED] Enable/Disable fullrowselect
* \[ADDED] Buttons on upper right corner
* \[ADDED] Button to update proxy stats manually
* \[ADDED] Start with Windows feature
* \[ADDED] Automatic update checking
* \[ADDED] Tick/Untick SSL proxies
* \[IMPROVED] Some optical improvements on lists on GUI
* \[IMPROVED] Disabled fullrowselect on lists (default settings)

### Version 2.01 (08-26-2016)

* \[FIXED] Minor Bugs
* \[IMPROVED] Proxy Source
* \[IMPROVED] Chart Stats
