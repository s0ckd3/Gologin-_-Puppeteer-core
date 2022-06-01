# Gologin-_-Puppeteer-core
Test Gologin Profile Offline with Puppeteer-core
```
    const activeextension = 'F:/tool_gmail/extension/active';
    const extension = `${Config.ProfileDir}/${profile}/extension`
    const browser = await puppeteer.launch({
    ignoreDefaultArgs: true,
    ignoreHTTPSErrors: true,
    defaultViewport: null,
    headless: false,
    chromiumSandbox: false,
    args: [
        '--lang=vi',
        '--tz=Asia/Bangkok',
        '--no-first-run',
        '--no-sandbox',
        '--font-masking-mode=2',
        '--origin-trial-disabled-features=ConditionalFocus',
        '--password-store=basic',
        '--disable-encryption',
        '--disable-blink-features=AutomationControlled',
        '--disable-infobars',
        '--disable-notifications',
        `--disable-extensions-except=${extension},${activeextension}`,
        `--load-extension=${extension},${activeextension}`,
        `--proxy-server=${newproxy}`,
        `--remote-debugging-port=${remote_debugging_port}`,
        `--user-data-dir=${Config.ProfileDir}/${profile}`
       
    ],
    executablePath: './browser/chrome.exe',

```


# Gologin-Profile-tool

Unlimited Gologin Profile Creation Tool
Using Gologin's Profile Offline, Not Depending on Gologin it's an absolute must. You will not have to worry about losing your Profile due to the server or any other reason. No data to download, no setup time...

1. Quickly create Gologin Profile Online.
2. Download for offline use on non-Gologin machines.
3. Easy to manage and modify.
4. Easily move data across computers without any worries.
5. No maintenance fee, Create a large number of Profiles without renting software.
6. Easy integration into automated browser controls. Combine Python, Nodejs, C#...

https://guidevn.com/bai-viet/tao-profile-trinh-duyet-gologin-offline-su-dung-offline-vinh-vien

Video: https://www.youtube.com/watch?v=yLE_wa5y95U

## Full code Contact:
- Email: Esale.safe@gmail.com
- TeleGram: https://t.me/shanghaz
- Facebook: https://www.facebook.com/guide.vnn

Note: We do not crack, do not use any interference with the software of the manufacturer and distributor of Gologin software.
