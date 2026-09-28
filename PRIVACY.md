# Finance Calculator — Privacy Policy

**Effective date:** 28 September 2026 (applies from app version 1.6.0)

Finance Calculator is a Reddit app that adds finance calculators to a subreddit as an interactive post. This policy explains what information the app handles. The short version: **the app does not collect, store or share your personal information.** The numbers you enter stay in your own browser. The app only keeps anonymous counts of how often it is used in each community, described below.

## Numbers you enter

Every number you type into a calculator — amounts, rates, durations, dates — is processed only in your own browser or Reddit app. These numbers are:

- not sent to the app's developer or to any server,
- not logged, counted or analysed, and
- kept only in your own browser, as described below, so each calculator opens with the values you entered last.

The calculators load no live market data. The only requests the app makes while you use it are the anonymous usage counts described in the next section; they never contain your numbers or results.

If you save a result as **scenario A** to compare it with another calculation, that scenario is kept only in memory and disappears when you close the calculator.

## Anonymous usage counts

To learn which calculators are useful, the app counts a few actions: opening the calculator post, opening a calculator, finishing a calculation, copying a share summary, comparing two scenarios, a calculation that ends with an input error, and the display language and whether the device is touch-first (counted as mobile) or not (both once per browser session). For each action, the app sends one small request to its own server on Reddit's developer platform that contains only the name of the action and, where relevant, which calculator, which language or mobile/desktop.

The server adds 1 to a daily total and to a running all-time total for the community where the app is installed. These totals:

- contain no user IDs, usernames, post or comment content, entered numbers or results,
- are not an event log; only the sum per day (and in total) for each action and calculator, language or device type is kept,
- are stored in the app's storage for that community on Reddit's developer platform, and
- are deleted automatically 90 days after the day they belong to (daily totals), or kept for as long as the app is installed in that community (all-time totals).

Moderators of that community can view the totals in the moderator menu and on a usage stats page inside the calculator post. The totals are not sent anywhere outside Reddit, and no third-party analytics service is used. If counting fails, the calculator keeps working normally.

## What is stored in your browser

The app uses your own browser's local storage, which only this app can read on your device:

- **Display settings:** your language, currency, color palette and light or dark choice, under `finance-calculator-language`, `finance-calculator-currency`, `finance-calculator-palette` and `finance-calculator-theme`.
- **Your last inputs:** the values you entered in each calculator, under `finance-calculator-inputs`. **Reset** in a calculator removes that calculator's values.
- **Recently used calculators:** the last three calculators you opened, under `finance-calculator-recent`.
- **Opening in full screen:** when you tap a calculator (or, as a moderator, the usage stats) in the post preview, the app briefly stores which one under `finance-calculator-open` so the full-screen view can show it. It is removed as soon as the full-screen view opens.
- **Session marker:** in your browser's session storage, `finance-calculator-language-tracked` notes that the display language and device type were already counted, so they are counted at most once per session. Your browser removes it when the session ends.

It stores nothing else there. You can remove all of this at any time by clearing your browser's site data.

The app sets no cookies of its own and uses no third-party analytics, advertising or tracking tools.

## Sharing a result

**Copy for Reddit** prepares a text summary of your scenario. Nothing is shared unless you copy that text yourself and paste it somewhere. The app never posts, comments or sends messages on your behalf.

## Moderator menu

When a moderator chooses **Create Finance Calculator** from the subreddit menu, the app uses information that Reddit provides for that action — the subreddit name, the moderator's user ID and username — to check that the person is a moderator of that subreddit. It then creates one calculator post. This information is used only for that check, is not stored by the app, and is not used for anything else.

When the app is installed in a community, it creates one calculator post there. It uses no personal information for that.

The same moderator check is used when a moderator opens **Finance Calculator: usage stats** in the moderator menu. To decide whether to show the usage stats page inside the calculator post, the app also asks Reddit whether the person viewing the post moderates that community; Reddit answers based on the viewer's user ID. The answer is used only for that page and is not stored. Both views only read the anonymous totals described above.

## Reddit

Finance Calculator runs on Reddit's developer platform. Your use of Reddit, including viewing and interacting with posts that contain this app, is also covered by [Reddit's Privacy Policy](https://www.reddit.com/policies/privacy-policy). The app's developer has no access to the information Reddit collects about you beyond what is described above.

## Children

The app is not directed at children and does not knowingly process children's personal information.

## Changes to this policy

If the app's handling of information changes, this policy will be updated and the effective date above will change. The current version is always available at this address.

## Contact

Questions about this policy can be raised as an issue in the project repository: https://github.com/huzLmyG/finance-calculator-legal/issues
