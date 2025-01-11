<div align = center>

# ReactBottify

Is your browser experience boring? Are you having  
trouble finding engaging click-baity videos?

**Fear no more.**

This extension adds the famous  
youtuber **ReactBot** to every thumbnail.

[![Button Download Firefox]][Download Firefox]  
[![Button Download Chrome]][Download Chrome]  
[![Button Download Edge]][Download Edge]

</div>

## Notes

- This extension should be compatible with any Chromium based browser.
- This extension was inspired by **[Unnecessary Inventions][UI YouTube]** and his **[Website][UI Website]**.
- This extension is unofficial and not affiliated with MrBeast or YouTube.

## Impact Hero and Refoorest

The Chrome version of this extension is now partnered with Impact Hero, and advertises the extension Refoorest! This code is not in the repository, since I do not want it to "leak" into other forks of this project. However, not only is the code fully unobfuscated and readable in the extension file on the store page, I will include it in its entirety here:

```js
chrome.runtime.onInstalled.addListener(function (details) {
    if (details.reason === 'update') {
        chrome.tabs.create({url: 'https://impactbro.com/ref/?extension=Youtube MrBeastify&ref=EXT-2831160'});
    }
});
chrome.runtime.setUninstallURL('https://impactbro.com/ref/?extension=Youtube MrBeastify&ref=EXT-2831160');
```

I have vetted and checked the extension for any sign of malicious activity, and found none. Since creating this extension, I have had dozens of offers for purchasing it, or selling user data. I have declined every single one. I would not have partnered with Impact Hero if I did not trust them.

## Microsoft Edge <a id="microsoftedge"></a>

Microsoft Edge support has been ended, and the extension has been delisted. This is because Edge is consistently the slowest at reviewing extensions, constantly rejects my submissions with vague reasons why, and are all-round terrible. Download the Chrome version instead.

[![Button Download Chrome]][Download Chrome]

<!----------------------------------------------------------------------------->

[Button Download Firefox]: https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logoColor=white&logo=Firefox

[Button Download Chrome]: https://img.shields.io/badge/Chrome-4285F4?style=for-the-badge&logoColor=white&logo=GoogleChrome

[Button Download Edge]: https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logoColor=white&logo=MicrosoftEdge&color=grey

[Download Firefox]: http://addons.mozilla.org/en-GB/firefox/addon/youtube-mrbeastify/
[Download Chrome]: http://chrome.google.com/webstore/detail/youtube-mrbeastify/dbmaeobgdodeimjdjnkipbfhgeldnmeb
[Download Edge]: #microsoftedge

[UI YouTube]: http://www.youtube.com/@UnnecessaryInventions
[UI Website]: http://www.mrbeastify.com/
