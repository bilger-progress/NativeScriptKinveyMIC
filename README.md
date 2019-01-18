# NativeScriptKinveyMIC
Cross-platform (Android &amp; iOS) application solution for integrating Kinvey Mobile Identity Connect.


In order to setup a test with the application, make sure to:

1. Open `kinvey.common.ts` file from inside the `src/app/shared` folder and set your Application ID and Application Secret (and Instance ID if present, if not - remove the attribute).
2. Open the `Login` component's TypeScript controller and set your _MIC_ identifier.
3. Open the _MIC Service_ settings from the __Kinvey Console__ and set `myscheme://` as a redirect URI.