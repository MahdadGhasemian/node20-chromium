# To use puppeteer

# Env

You can use the `CHROMIUM_PATH` env in your app for the puppeter path.

## Env Example:

```
options = {
    executablePath: process.env.CHROMIUM_PATH,
    headless: 'new',
    args: [
        '--no-sandbox',
        '--disable-setuid-sandbox',
        '--disable-web-security',
        '--font-render-hinting=none',
        '--allow-file-access-from-files',
        '--enable-local-file-accesses',
    ],
    ignoreDefaultArgs: ['--disable-extensions']
};
```
