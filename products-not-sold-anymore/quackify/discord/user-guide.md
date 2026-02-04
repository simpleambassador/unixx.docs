---
description: This documentation provides everything you need to know for using Restorio.
---

# ⌨️ User Guide

## Full Guide

This is a official guide provided by the developer of the selfbot<br>

#### Claiming your license

1. Go to [**https://never.regret.today/auth/register**](https://never.regret.today/auth/register) **and register an account**
2. Once logged in, hit Settings in the sidebar → scroll to Add License → drop your key and boom, redeemed.
3. After the license has been successfully redeemed, refresh the page and navigate back to the Overview section. Your product details and download links will now be displayed.
4. Download the build compatible with your operating system and launch the executable. The setup process is fully guided and automated from that point onward.

\
\
\
To retrieve your Discord token, navigate to[ ](https://discord.com/channels/@me)[https://discord.com/channels/@me/](https://discord.com/channels/@me/), press F12 to open Developer Tools, switch to the Console tab, paste the script below, and your token will be automatically copied to your clipboard:\
<br>

```javascript
window.webpackChunkdiscord_app.push([
	[Symbol()],
	{},
	req => {
		if (!req.c) return;
		for (let m of Object.values(req.c)) {
			try {
				if (!m.exports || m.exports === window) continue;
				if (m.exports?.getToken) return copy(m.exports.getToken());
				for (let ex in m.exports) {
					if (m.exports?.[ex]?.getToken && m.exports[ex][Symbol.toStringTag] !== 'IntlMessagesProxy') return copy(m.exports[ex].getToken());
				}
			} catch {}
		}
	},
]);

window.webpackChunkdiscord_app.pop();
console.log('%cWorked!', 'font-size: 50px');
console.log(`%cYou now have your token in the clipboard!`, 'font-size: 16px');
```
