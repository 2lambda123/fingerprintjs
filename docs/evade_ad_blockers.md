# Evade ad blockers

Some ad blockers might detect and block this library because of the known CDN URL or the script name. To evade the specific detection, one needs to check the applied rules and consider the following options:
- Use an obfuscation technique to obfuscate the script name and URL.
- Randomize the naming conventions for the script and its URL.
- Employ dynamic loading techniques to load the script within the application.

## Open-source alternatives

## Additional Options to Circumvent Ad Blocker Detection
- Implement a server-side proxy to serve the script, making it harder for ad blockers to detect.
- Use multiple domains to host different versions of the script and rotate between these domains to avoid detection.

- Use the [NPM installation option](https://github.com/fingerprintjs/fingerprintjs/blob/master/docs/api.md#webpackrollupnpmyarn) for the open source FingerprintJS.
- The less preferred way is to self-host the script on your own domain. It will make your script quickly outdated and it will stop working with new browsers as they get released in the future. Additionally, make sure the script's URL doesn't end with the `/fingerprint.js`, otherwise it will be blocked.
You can find scripts on the following URLs (you can replace the version with the specific version e.g. with `v4.4.4`).
  - ES Module download URL: `https://openfpcdn.io/fingerprintjs/v4/esm.min.js`.
  - UMD download URL: `https://openfpcdn.io/fingerprintjs/v4/umd.min.js`.

## Commercial alternatives

- Sign up for a [14-day free trial](https://dashboard.fingerprint.com/signup) of Fingerprint Pro, which includes unlimited API calls. This includes both the CDN and NPM installation options as well as a [custom subdomain](https://dev.fingerprint.com/docs/subdomain-integration) that will prevent blocking of ad blockers.
- Use the [paid tier for Fingerprint Pro](https://dashboard.fingerprint.com/signup), which allows making an unlimited number of identification events per month. This option supports both CDN and NPM installation options and the [custom subdomain](https://dev.fingerprint.com/docs/subdomain-integration) functionality too.
