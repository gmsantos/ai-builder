# Transition to use a new form processing model version

Any form processing preview models created before March 5, 2020 will be deprecated. Until June 8, 2020, these models will continue to function, and Microsoft will continue to provide support, however some functionality may be disabled. After June 8, 2020, these models will no longer function.

Beginning March 5, you will need to recreate your existing form processing models with the new model versions. Any models created after this date will automatically use the new model versions and require no action. You are encouraged to transition to use the new model version as soon as possible.

## What do I need to do?

**You need to recreate any form processing model created before March 5, 2020**

1.	Identify any form processing models created before March 5, 2020 that you want to continue using.
2.	For each model, [recreate a new form processing model](https://docs.microsoft.com/ai-builder/create-form-processing-model) with the same training documents you used in the original model.
3.	Once the new model has been trained and published, make sure to update any apps or flows to use the new model.
4.	After you finish using your deprecated form processing model, you can delete it. 

We understand that some of you may have invested a significant amount of time tagging your form processing models. Feel free to [contact us](mailto:aihelpen@microsoft.com) and we may be able to help migrate your larger models in a more expedited manner.

## Why this change?
Form processing models are being upgraded to become generally available, but existing preview models will not be compatible with the new model version.

Until March 5, 2020, form processing models stored images as attachments in the Note entity. With this update, these models now leverage the new [File and Image datatypes](https://powerapps.microsoft.com/blog/introducing-improvements-to-data-storage-in-common-data-services/) in Common Data Service, enabling a better and more optimized usage of capacity.
