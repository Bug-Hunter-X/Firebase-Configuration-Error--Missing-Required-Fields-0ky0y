# Firebase Configuration Error: Missing Required Fields

This repository demonstrates a common error when initializing the Firebase SDK: providing an incomplete configuration object.  Missing required fields in `firebaseConfig` can lead to unexpected behavior and app crashes.  The `firebaseBug.js` file shows the problematic code, while `firebaseBugSolution.js` provides a corrected version.

## Steps to Reproduce

1. Clone this repository.
2. Run `firebaseBug.js` (you'll need to replace placeholders with your actual Firebase config, except for the intentionally missing fields). Observe the error.
3. Run `firebaseBugSolution.js`. Observe successful initialization.

## Solution

Ensure your `firebaseConfig` object includes *all* required fields. Refer to the official Firebase documentation for the complete list of required configuration parameters.