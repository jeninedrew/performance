# performance

## Performance Budget and Review

### Tools

http://www.performancebudget.io/

https://whatdoesmysitecost.com/

https://browserdiet.com/calories/

https://github.com/pa11y/pa11y [good explainer](https://bitsofco.de/pa11y/)

### Overview

- A starting point for site optimization conversations
- Balance user experience with browser experience
- Look at competitor sites 
- Consider user analytics (mobile? connection?)
- Set goals

### Budget (Competive Analysis)

- Start Render
- Doc Complete
- Fully Loaded

- [Speed Index](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index)

[Resource](https://docs.google.com/spreadsheets/d/1ifac_Z-P9IgjzVZIWPV2qdugtwJ3HA9dkhvKmPUXBLo/edit#gid=0)

### Budget (Ideas)

- Maximum size of the images you are willing to upload to your website (before or after compression) to maintain as small page weight as possible
- Total number of HTTP requests allowed per page
- Maximum page weight totals
- Setting a threshold to achieve using Google’s Speed Index
- Limits on segmented scripts such as JavaScript, CSS, web fonts
- Total load time not to exceed a certain number (seconds or ms)
- Google fonts, local fonts, or system fonts (read our case study on web font performance)
- Number of external resources (perhaps you choose to migrate some 3rd party assets, if possible, to your own CDN)
	- Migrate Google Fonts to your CDN
	- Host Analytics Locally and on your CDN

[Resource](https://www.keycdn.com/blog/web-performance-budget/)

## Resources

[Chrome DevTools- Performance monitor](https://hospodarets.com/chrome-devtools-performance-monitor)

http://www.webpagetest.org/ ([Docs](https://sites.google.com/a/webpagetest.org/docs/))

http://yslow.org/

https://tools.pingdom.com/

https://developers.google.com/speed/pagespeed/insights/

https://www.webpagetest.org/easy (test slow connections)

https://search.google.com/search-console/mobile-friendly (mobile friendly)

Chrome's Lighthouse is now in Dev tools! (Audits tab)

## Read These

https://medium.com/@fox/talk-the-state-of-the-web-3e12f8e413b3

https://infrequently.org/2017/10/can-you-afford-it-real-world-web-performance-budgets/
