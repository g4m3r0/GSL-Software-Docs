---
description: Traffic Buddy V2 Software Guide
---

# 📖 Software Guide

Welcome to the Traffic Buddy User Manual, your comprehensive guide to mastering our platform's versatile features. Here, you'll discover how to manage campaigns, leverage custom JavaScript plugins for interactive web interactions, and adjust browser and proxy settings for optimized browsing experiences.

Learn how to add campaigns, customize viewing metrics, and automate user behavior. Harness the power of plugins to interact with specific websites and set up advanced proxy settings for secure browsing. With Traffic Buddy, managing multiple Chromium-based browsers or configuring your traffic's origin is just a click away.

This manual will serve as your go-to resource, whether you're a new user or a seasoned veteran, on your journey towards creating powerful and automated browsing experiences with Traffic Buddy.

### Quick Start Guide

TODO: Gif of adding a campaign



### Campaigns

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption><p>Add Campaign Overview</p></figcaption></figure>

In the Campaign tab, a comprehensive list of all campaigns can be found on the left side. Simultaneously, the right side displays an embedded view of all the Chromium-based browsers currently in operation.

Traffic Buddy provides a user-friendly interface, featuring buttons located below the campaign list, that enables you to manage your campaigns efficiently. These functions include the ability to add, edit, or remove campaigns, as well as start, stop, or reset them, providing complete control over your campaign management process.

<table data-view="cards"><thead><tr><th>Button</th><th>Description</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (22).png" alt=""></td><td>Add new Campaign</td></tr><tr><td><img src="../../.gitbook/assets/image (8).png" alt=""></td><td>Edit selected Campaign</td></tr><tr><td><img src="../../.gitbook/assets/image (16).png" alt=""></td><td>Remove selected Campaign</td></tr><tr><td><img src="../../.gitbook/assets/image (11).png" alt=""></td><td>Start selected Campaign</td></tr><tr><td><img src="../../.gitbook/assets/image (2).png" alt=""></td><td>Stop selected Campaign</td></tr><tr><td><img src="../../.gitbook/assets/image (20).png" alt=""></td><td>Reset view counter of selected campaign</td></tr></tbody></table>

### Add Campaign

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption><p>Add new Campaign</p></figcaption></figure>

When you're ready to add a new campaign in Traffic Buddy, a variety of settings can be tailored to suit your needs. First, you'll be prompted to specify the website URL for the campaign. This is the primary webpage that your campaign will target.

Next, you can set the number of threads for your campaign. Each thread corresponds to a separate Chromium-based web browser that will interact with the specified website, offering a scalable approach to manage your browsing sessions.

After that, you can determine the number of views that your campaign will generate. Along with the views, you can also define the duration of the watch time on the website. This allows for more precise interaction with the website in terms of user engagement metrics.

In addition, you can control the delay between views. This ensures the views appear natural and organically spread over time, rather than occurring simultaneously.

Another powerful feature is setting the origin, or the referrer, of the traffic. This can either be direct, from a search engine such as Google with a specific keyword like "SEO Application," or from multiple referrers. If multiple referrers are chosen, they will be selected randomly, further mimicking organic user behavior.

Finally, you also have the option to explore and interact with inner URLs of the website. This feature enhances the browsing session to mimic more engaged user behavior by visiting various pages of the website. You can determine the watch time, delay, and the number of inner pages that should be visited, allowing for a deeper and more comprehensive interaction with the site during each browsing session.

### Proxy Settings

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption><p>Proxy Settings</p></figcaption></figure>

The Proxy Settings in Traffic Buddy provide a feature to configure the use of a proxy server for website browsing. The application supports various proxy protocols including HTTP, HTTPS, Socks4, and Socks5. You can add new proxy servers by navigating to the "Proxy" option in the top menu strip.

For convenience, Traffic Buddy also offers the ability to download a list of pre-scraped and tested public proxy servers.

Additional settings provide enhanced control over your browsing experience. Features include the ability to disable non-functional proxies, verify proxy servers before engaging them with the web browser, and filter proxy servers by country, allowing users to exclude proxies from one or multiple countries.

We are also excited to announce that support for Tor proxies will be integrated into our system in the near future. This upcoming feature will provide our users with another layer of security and anonymity during web browsing.

### Browser Settings

<figure><img src="../../.gitbook/assets/image (23).png" alt=""><figcaption><p>Browser Settings</p></figcaption></figure>

The Browser Settings in Traffic Buddy provide users with the flexibility to modify various browsing preferences at a global level. These options include enabling or disabling the execution of JavaScript, controlling the loading of images, as well as setting the browser's locale and language. This feature ensures a more personalized and optimized browsing experience.

### Plugins

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption><p>Plugins</p></figcaption></figure>

Plugins in Traffic Buddy are custom-built JavaScript snippets purpose-built to engage with specified websites. These scripts empower advanced features such as the simulation of user interactions — for instance, clicking on predetermined buttons, or orchestrating a sequence of automated actions. This capability fosters an experience that is both interactive and personalized, enhancing the automated browsing process.

Furthermore, these plugins are designed to be triggered automatically when the URL of the website includes the predefined "URL contains" variable, ensuring seamless interaction with the desired elements of the site.

<table data-view="cards"><thead><tr><th>Button</th><th>Description</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/image (22).png" alt=""></td><td>Add new Plugin</td></tr><tr><td><img src="../../.gitbook/assets/image (16).png" alt=""></td><td>Remove selected Plugin</td></tr></tbody></table>

### Add Plugin

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Add new Plugin</p></figcaption></figure>

When introducing a new plugin to Traffic Buddy, various settings can be tailored to meet your needs. Firstly, you will need to designate a unique 'Plugin Name' to identify the plugin within the system.

Next, you'll define the 'JavaScript Code' to be executed. This is where you provide the custom JavaScript that the plugin will run on the target website.

Further customization is allowed with 'Execution Delays.' You can set both a 'Delay Before Execution,' which is a pause before the JavaScript is run, and a 'Delay After Execution,' which is a pause following the completion of the script. These delays provide control over the timing of the plugin's operation and can be tailored to mimic real user behaviors or meet specific website requirements.

An important feature to note is the 'URL Must Contain' field. Here, you enter a specific string, and the JavaScript will only be executed if the website's URL contains this string. This enables the automatic and targeted execution of plugins on the appropriate web pages.

Finally, if you wish to monitor the execution of the plugin and any potential output, you can enable the 'Output Log to the Console' option. This feature logs the results of the plugin's execution to the system's console, allowing for easy tracking and debugging.
