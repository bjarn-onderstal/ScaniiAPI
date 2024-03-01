Virusscanner by Scanii

General
With this module you can scan your files for malicious or unsafe conent by Scanii. Scanii will check if the file (and the content) is malicious or unsafe. 
The result will be empty or with findings. If it's empty, the file is safe. If it has findings, it's unsafe or malicious. 
It's up to you to decide if you want to keep the file or not.

For daily use you need to have a subscription:
https://scanii.com/pricing

Instructions
1. Create an account at www.scanii.com;
2. Copy the 'API Key' from your Scanii account;
3. Change the constant 'APIKey' to your APIKey value;
4. Copy the 'Secret Key' from your Scanii account;
5. Change the constant 'APISecret' to your APISecret value;
6. Change the constant 'EnvironmentURL' to your environment URL;
7. Choose the correct Scanii region to use for scanning and copy the URL to clipboard. You can find the locations in the documentation of the 'ScaniiBaseURL' constant;
8. Paste the region URL in the constant 'ScaniiBaseUrl';
9. Implement the the synchronous or asynchronous sub in your logic and you'are ready to go!
