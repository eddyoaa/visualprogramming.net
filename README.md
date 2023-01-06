# visualprogramming.net

The new website for vvvv.

Local build:
* download Hugo Extended, unzip and place that into your programs folder,
* add it to your path (environment variables),
* powershell: 
  * cd C:\dev\visualprogramming.net
  * hugo server
* open http://localhost:1313/ in your browser

To run in the browser and to be able to access the site from the same local wifi (eg. checking on mobile), run hugo with:
`hugo serve --bind 0.0.0.0 --baseURL http://IP:1313` where IP is your IP from `ipconfig`

### Shortcodes:

__Mastodon:__  
{{< mastodon "mastodon.xyz/@vvvv/109598445063555699" 550 >}}  
Parameters: Link [Height (default=550)]

__Pixelfed:__  
{{< pixelfed "pixelfed.social/p/madewithvvvv/509678388578111219" 550 >}}  
Parameters: Link [Height (default=550)]

__Vimeo:__  
{{< vimeo 761078720 >}}  
Parameters: Vimeo ID

__Youtube:__  
{{< youtube 761078720 >}}  
Parameters: Youtube ID