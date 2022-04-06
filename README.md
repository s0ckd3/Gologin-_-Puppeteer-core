# Gologin-_-Puppeteer-core
Test Gologin Profile Offline with Puppeteer-core
**
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
        args: [
          
        ],
        // userDataDir: `${Config.ProfileDir}/${profile}`,
    });
**
