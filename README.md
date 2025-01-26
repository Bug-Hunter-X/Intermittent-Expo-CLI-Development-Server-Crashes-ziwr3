# Intermittent Expo CLI Development Server Crashes

This repository demonstrates a bug encountered with the Expo CLI development server where it would intermittently crash without providing clear error messages. The server would become unresponsive, displaying a blank screen in the browser.  The issue was inconsistent, sometimes crashing frequently and other times working without issue for extended periods.

## Reproduction

The provided `expoBug.js` file (intentionally empty) simulates the application where the crash occurred.  The crash was not reproducible by any specific code snippet and seemed related to memory or resource exhaustion.  The solution focuses on preventative measures rather than directly addressing a specific error in the code.

## Solution

The `expoBugSolution.js` provides a set of recommended solutions which focuses on optimizing the development environment to prevent these crashes from occurring.  These solutions include checking for memory leaks in the application code, upgrading Expo CLI and related dependencies, increasing system resources allocated for the development server, and trying different development server options.

## Contributing

Contributions are welcome! If you have encountered similar issues or discovered additional solutions, please feel free to open a pull request.