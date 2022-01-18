## Quick Start

1. Press on *Autopilot* to automatically download proxy source from our server and the testing process will be started. Working proxy server will be added to the *Proxy List*.

![Autopilot](assets/img/autopilot.gif)

**OR**

1. *Import* Proxy Sources to scrape proxies from.
2. *Scrape* the imported sources for proxies.
3. *Test* the scraped proxies.
4. *Export* the the working proxies according to your needs.

## Autopilot

The *Autopilot* will scrape proxy source and test the found proxies afterwards. Proxy Sources will be dowloaded from GSL if there are no proxy source inside the list. Working proxy server will be added to the *Proxy List*.

## Proxy Tester

Proxy Buddy is the fastest proxy tester on the market for Windows Desktop. With socket-based multi-threading support, it can test more than 10.000 proxies every minute. It tests proxies for Google Pass (Google Search) and determines the country, speed, anonymity, SSL support, and the used protocol (HTTP, HTTPS, SOCK4, SOCKS5). The proxy server’s IP address will be checked for blacklisting in the stopforumspam database as well.

### Proxy List

![Proxy List](assets/img/proxy_list.png)

|Function | Description
--- | ---
|Host
|Port
|Status
|Google Search
|Country
|Speed
|Anonimity
|Protocol
|Uptime
|U
|D
|Blacklisted
|Last update

### Context Menu

![Proxy List Context Menu](assets/img/proxy_list_context_menu.png)

|Function | Description
--- | ---
|Tick
|Copy

### Status

## Proxy Scraper

Proxy Buddy is the best proxy scraper software. It comes with a built-in list of fresh proxy sources. These allows to easily scrape huge lists of Google proxies each and every day. Found proxy lists can be used with all popular SEO software, SEO tools, and bots, including but not limited to GSA Search Engine Ranker, SENuke, Scrapebox.

### Source List

![Source List](assets/img/source_list_blured.png)

|Function | Description
--- | ---
|Status| The status of the source (Scrapen, NotScraped, Down).
|URL| The URL of the proxy source.
|Proxies found| The amount of proxies found.
|Quality| The calculated quality.
|Last update| The last time the source was updated.

### Context Menu

![Source List Context Menu](assets/img/source_list_context_menu.png)

|Function | Description
--- | ---
|Tick All| Tick the checkbox of all sources.
|Tick None| Untick the checkbox of all sources.
|Calculate Qualits| Calculate the quality of the sources according to the tested proxies.

### Status
The status bar at the bottom of the source list shows the amount of proxy sources inside the list.

## Task Scheduler

![Task Scheduler](assets/img/task_list.png)

### Action

![Action](assets/img/task_action.png)

### Filter

![Filter](assets/img/task_filter.png)

## Top Menu

### Autopilot

The *Autopilot* will scrape proxy source and test the found proxies afterwards. Proxy Sources will be dowloaded from GSL if there are no proxy source inside the list. Working proxy server will be added to the *Proxy List*.

### Import

![Import](assets/img/top_import.png)

### Export

![Export](assets/img/top_export.png)

### Remove

![Remove](assets/img/top_remove.png)

### Stop
Stop all current operations. It can take some minutes until all threads are shutdown.

### Help
Opens the link to the help page with the software manual.

## Settings
On the *Settings* tab several software parameters can be adjusted. The settings tab can be found in the top menu.

### General Settings

![General Settings](assets/img/settings_general.png)

**Thread Settings**
|Function | Description
--- | ---
|Maximum Test-Threads| Set the maximum amount of threads used to test proxies.
|Maximum Scrape-Threads| Set the maximum amount of threads used to scrape proxies from the proxy source.
|Timeout in seconds| Set the timeount in seconds.

**General Settings**
|Function | Description
--- | ---
|Start with Windows| Start Proxy Buddy with Windows.
|Enable GridLines| Enable gridlines on all lists.
|Enable Full-Row-Select| Enable full row select on all lists.
|Visual Theme| Select a theme to change the visual presence.
|Enable Debug Mode| Enables the debug mode which prints additional information to the logfile.
|Reduce CPU usage| Reduce the CPU usage by disabling visual features.

**Save Settings**
|Function | Description
--- | ---
|Save Settings on exit| Save the settings when the program shuts down.
|Save Proxy List on exit| Save the proxy list when the program shuts down.
|Save Source List on exit| Save the source list when the program shuts down.
|Automatically create database backups| Automatically create backup files of the proxy and source database.
|Create Backup now| Create a backup of the proxy and source database now.

**License Settings**
|Function | Description
--- | ---
|License Key| Displays the activated license key.
|License Type| Display the license type of the activated license key.
|Remove License| Remove the activated license from the software.

### Test Settings

![Test Settings](assets/img/settings_test.png)

**Google Settings**
|Function | Description
--- | ---
|Test for Google search pass| Test if a proxy can search/scrape google.
|Google Search Test URL| Set the URL which is used to test the google pass. 

**General Test Settings**
|Function | Description
--- | ---
|Test server location| Determine the coutry of the proxy server while testing.
|Test Anonymity| Determine the anonimity level while testing (Transparen, Anonymous, Elite).
|Use public proxy judge| Use a custom/public proxy judges for determining the anonimity level of proxy servers.
|Test HTTP protocol| Test if the proxy supports the HTTP protocol.
|Test HTTPS support| Test if the proxy supports the HTTPS/SSL.
|Test Socks4 protocol| Test if the proxy supports the Socks4 protocol.
|Test Socks5 protocol| Test if the proxy supports the Socks5 protocol.

**Test and Scrape (Auto) Settings**
|Function | Description
--- | ---
|Stop Test and Scrape (Auto) when found x workinig proxies.| Stop the autopilot when x amount of working proxies were found.
|Only add up/online proxies to the Proxy List.| Only add proxies that are up/online to the proxy list.

**Duplicate Settings**
|Function | Description
--- | ---
|Automatically remove duplicates| Automatically remove duplicate proxies when importing or scraping proxies.
|Automatically remove invalid proxies| Automatically remove invalid proxies from the proxy list while testing.

### E-Mail Settings

![E-Mail Settings](assets/img/settings_email.png)

**E-Mail Settings**
|Function | Description
--- | ---
|SMTP Server
|SMTP Port
|SMTP Username
|SMTP Password
|E-Mail From
|Subject
|Body
|Enable SSL
|Maximum amount of proxies sent
|Attach proxies as text file (else append them to body)

**E-Mail Receiver List**
|Function | Description
--- | ---
|Manually Send E-Mails| Manually send E-Mail with proxies to the E-Mails listed below. 
|Add E-Mail| Add an E-Mail to the E-Mail list.
|Email| The E-Mail that should be added to the list.
|Remove selected E-Mail| Remove the selected E-Mail from the list.

### Upload Settings

![Upload Settings](assets/img/settings_ftp.png)

|Function | Description
--- | ---
|FTP Server
|FTP Path + Filename
|FTP Username
|FTP Password
|Limit uploaded proxies to
|Manually Upload

### Error Log

![Error Log](assets/img/settings_error_log.png)

|Function | Description
--- | ---
|Refresh Logfile| Read the logfile and display it.
|Clear Logs and Logfile| Clears the logfile.