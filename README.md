# IDCSBiometric
We integrate Daon's API with Oracle Identity Cloud Service to allow users log in via fingerprint, voice and facial recognition.

Configuration: 
1. Follow instructions to set up a third party application "Cquotes" and allows IDCS to become the service provider of that app. Guidance: https://www.oracle.com/webfolder/technetwork/tutorials/obe/cloud/idcs/idcs_clientapp_obe/clientapp.html#section1s2
2. Import the licenses(daon.cer, daonTest.cer) to your local machine's keystore.
3. Register an account in IDCS, for example: abc@oracle.com.
4. Get access to Daon's Admin Page and create a user with the same username(abc@oracle.com)e as Step 3.
5. Download the app identityX from Apple Store and scan the code from Daon's user registration page.
6. Run the app.
