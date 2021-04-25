**Edit a file, create a new file, and clone from Bitbucket in under 2 minutes**

This repository contains the data and source code for the aspect extraction task from "" . 
It consists of a collection of messages related to stock investments that have been annotated with Aspects(opinions labels).
---

## Annotations
messages_aspects.json contains a json where the key: "Messages" store a list of json for each message
Each message in messages_aspects.json is annotated with the following information:

1. `Aspect_Class`: Class annotated by a financial expert
2. `Aspect_Subclass`: A more detailed class annotated by a financial expert
3. `Message`: Message written by an user
4. `Sentiment`: a floating point value between `-1` (very bearish/negative) and `1` (very bullish/positive) denoting the sentiment expressed towards `company`. `0` denotes neutral sentiment.
5. `Span`: annotated part of the message that lead the financial expert to label the Aspect

---



## LICENSES
The annotations are licensed under the Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. Please cite the aspect extraction task paper when using this dataset.

If you are interested in commercial use of these data, please [contact the SSIX consortium|http://ssix-project.eu/contact-us/].


## Acknowledgements
These resources were created in the context of the SSIX project. This project has received funding from the European Union's Horizon 2020 research and innovation programme under grant agreement No 645425.
