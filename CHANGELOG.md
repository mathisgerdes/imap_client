## 0.2.1

- Fix #4, bug that prevented mailboxes with spaces from being opened
- Fix #7, bug that did not acknowledge escaped characters
- Fix #8, add missing imap 4 rev 1 commands (subscribe, unsubscribe, lsub)

## 0.2.0

- Version change, 1.0.0-alpha is lower than 0.1.3, which causes updates to fail

## 1.0.0-alpha

- Complete rewrite
- Now easier to use and extend
- Fix #2, a bug that prevents fetches
- Change concept of folders to representation based instead of internal handling

## 0.1.3

- Update test package to latest version
- Do travis tests on stable, now that dart v2 is out of dev

## 0.1.2

- Implement logging. Use printImapClientDebugLog() to display it.

## 0.1.1

- Fix errors caused by older dart version 2.0.0-dev.63.0
- Set minimum required sdk version to 2.0.0-dev.63.0

## 0.1.0

- Initial version
