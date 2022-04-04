# Custom Neural Voice Lite

Custom Neural Voice (CNV) Lite is a new project type in public preview. You can demo and evaluate Custom Neural Voice before investing in professional recordings to create a higher-quality voice.

With a CNV Lite project, you record your voice online by reading 20-50 pre-defined scripts provided by Microsoft. After you've recorded at least 20 samples, you can start to train a model. Once the model is trained successfully, you can review the model and check out 20 output samples produced with another set of pre-defined scripts.

Full access to Custom Neural Voice is required if you want to deploy a CNV Lite model and use it beyond reading the pre-defined scripts. A verbal statement recorded by the voice talent is also required before you can deploy the model for your business use.


## Getting started

The 'data labeling' part of this workshop will take about 20 minutes. The training part will take about 1 hour, however you can start with the Document Translation workshop and the model will be created in the background.

In this workshop we use CNV Lite, but it is good to [understand the differences between CNV Lite and Pro](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/custom-neural-voice#custom-neural-voice-project-types).

1. Open the [Speech Studio](https://speech.microsoft.com/) (speech.microsoft.com)

2. Select 'Custom Voice'

3. It will prompt you for a Subscription and a Resource. In case you don't have a resource yet, select 'Create a new resource'. 

    1. You can use your Azure Pass subscription where you create a new resource group.
    1. Create a new resource in the 'UK South' region, with the 'Standard S0' pricing tier. 

4. Select Custom Neural Voice LIte (beta) and press 'Next'.

5. Create a new project by giving it a name, selecting the gender and the language. 

6. You will now see the 'Record and build' page, and we are able to get started with the data labeling.

## Data labeling

1. On the main page ('Record and build'), press the blue 'Get started' button.

2. Read the voice talent term of use, and include your voice talent name and email address.

3. Now start the noise check. When you do this for the first time, your browser will ask for permissions to use your microphone.
    * If you have multiple microphones, make sure to select the right one.
    * If you a single microphone and are currently in a Teams meeting, it could be that your microfone is in use. Leave the Teams meeting temporarily during the recording and data labeling.

4. You can now start recording the sentences using the interface. There will be feedback on different areas and it will show you how to improve the recordings.

5. Continue step 4 until you have 20 samples. Now press 'Train model'.

    * After the workshop you can record more samples to improve the quality, however this will also raise the training time, thus keep it to 20 for now.

6. Now you will need to wait. This is a good time to start the next workshop of today, [Get started with Document Translation (Azure Translator)](DocumentTranslation.md).


## Resources

[Custom Neural Voice overview](https://docs.microsoft.com/en-us/azure/cognitive-services/speech-service/custom-neural-voice)

## Next: [Assignment 2: Document Translation](DocumentTranslation.md)