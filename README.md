Package `ua.Parse(userAgent string)` function parses browser's and bot's user agents strings and determins:
+ User agent name and version (Chrome, Firefox, Googlebot, etc.)
+ Operating system name and version  (Windows, Android, iOS etc.)
+ Device type (mobile, desktop, tablet, bot)
+ Device name if available (iPhone, iPad, Huawei VNS-L21)
+ URL provided by the bot (http://www.google.com/bot.html etc.)

## Notice

+ Opera and Opera Mini are two browsers, since they operate on very different ways.
+ If Googlebot (or any other bot) is detected and it is using its mobile crawler, both `bot` and `mobile` flags will be set to `true`.



