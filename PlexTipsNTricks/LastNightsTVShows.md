So I use causefx/Organizr as my framework for the website. When he released the show playlist functionality,
I realized that this could be used as a much better way to view "DVR" - *what is that again??*
<img src="https://user-images.githubusercontent.com/23283167/28600557-b766061a-7180-11e7-98f0-a85065bf19c2.png" width="100%">
*This was actually derived from creating a Arrowverse Playlist found somewhere on the r/Plex reddit...*

1. Open Plex, go to your TV Shows.
2. Select `TV Shows` and switch it to `Episodes`
3. Select All and switch it to `Custom Filter`
4. Change the `Show Title` Dropdown to `Air Date`
5. `is before` to `in the last`
6. Type `48` # more on this later
7. `Seconds` to `Hours`
8. Apply
9. Click the `Add to Playlist` button, it looks like a list with a plus sign.
10. New Playlist - `Last Nights TV Shows` - Enter! *I ended up naming mine `1 Last Nights TV Shows`*
  - If you are using layer#cake, Plex sorts by #, there is an add-on that removes the first number and space now.
  - https://github.com/leram84/layer.Cake/blob/master/Add-Ons/Numbered-Plist-Fix.css < paste that into your addons section

## This is what your Filter should look like!!
<img src="https://user-images.githubusercontent.com/23283167/28600567-bf3e9776-7180-11e7-91c0-d6ef8f6c491d.png" width="100%">

You now have an auto updating, auto cleansing playlist that will keep the shows that aired *LAST* night in plex.

##UPDATES
 - So, Plex includes any FUTURE episodes as included in the last 48 hours...I have no figured out a way to avoid this yet.
