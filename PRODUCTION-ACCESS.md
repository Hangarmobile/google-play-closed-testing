# The production access form

After the test, **Apply for production** on the Play Console dashboard opens a form in three parts (source: [Play Console Help](https://support.google.com/googleplay/android-developer/answer/14151465)). Be specific and honest: numbers, devices, bugs, fixes.

## Part 1: About your closed test

1. **How easy was it to recruit testers?** A simple choice. "Difficult" is a fine, common answer.
2. **Tester engagement.** Did testers use all features? Did usage match what you expect in production, and what differed?
   - Weak: "Testers used the app regularly and everything worked well."
   - Strong: "14 testers opted in, 12 used the app at least every other day. Most used the core flow. PDF export was used by only 3 testers, so we made it easier to find in v1.2. 9 phone models from 6 brands, Android 11 to 15."
3. **Feedback and how you collected it.**
   - Weak: "We got positive feedback."
   - Strong: "Shared form, group chat and Android vitals. Main points: sign-up button hidden on small screens, an English system dialog in the French version, a blank startup screen on one Huawei phone."

## Part 2: About your app or game

4. **Target audience.** Be as specific as possible ("freelancers in France who send fewer than 50 invoices a month", not "everyone").
5. **Value proposition.** How the app helps users, or what makes the game unique. Two or three concrete sentences.
6. **Estimated installs in the first year.** Pick a realistic range.

## Part 3: About your production readiness

7. **What did you change based on the test?**
   - Weak: "We fixed some bugs."
   - Strong: "2 updates during the test. v1.1 moved the sign-up button above the fold and replaced the English dialog. v1.2 fixed the blank startup screen on older WebView versions, confirmed by the tester on that phone."
8. **How did you decide the app was ready?** "No crashes or ANRs in the last 7 days, every reported bug fixed and re-checked, core flow completed on all 9 test devices."

## If Google asks for more testing

Keep the closed test running with testers opted in and active, ship another improvement, and reapply with better answers.
