# Expo CLI: Uncommon Bundler Errors

This repository demonstrates a common yet cryptic issue encountered when using the Expo CLI's `expo start` command.  The Metro bundler, responsible for compiling your JavaScript code, hangs or provides insufficient error messages, preventing the development server from starting.  This often points to problems within your app's dependencies, code syntax, or Expo's configuration.

## Reproducing the Issue

The `uncommonBug.js` file showcases a potential problem.  Run `expo start` and observe the behavior.  The exact error will likely vary based on the system and project setup but typically involves a crash or a long hang without a clear error message.

## Solution

The `uncommonBugSolution.js` file offers a resolution.  This often involves troubleshooting dependencies, fixing syntax errors, or ensuring the proper Expo configuration (especially the package.json and app.json files).  Careful examination of the console logs, including stack traces if available, is crucial for pinpointing the source of the problem. 