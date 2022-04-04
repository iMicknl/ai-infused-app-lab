## Document Translation

In this Hands-on tutorial you will be able to work with the Microsoft Document Translator, which is a part of the Microsoft Translator Service. 

This service allows you to batch translate a wide variety of documents while retaining their formatting. The advantages of the service compared to the regular translator is: 
- Supports larger batches of text than the regular translation service (Max is 40MB or 1000 Files or batch size of 250MB)
- Generally retains document formatting well
- Can translate from one source to multiple languages in one go (Max is 10)

Important to note about this service:
- It requires a Translator resource in Azure - This functionality is not supported in the broad cognitive services resource
- It is not supported in the free tier of the Translator resource
- it can be deployed as GLOBAL or LOCAL resource. This impacts your ability to use system-assigned authentication
- You need to use the custom domain name endpoint, not a general one
- Supports use of custom translation or use of glossaries

Since time is important please follow the guidelines in the below tutorial: 

[Document translation](https://docs.microsoft.com/en-us/azure/cognitive-services/translator/document-translation/get-started-with-document-translation?tabs=csharp)