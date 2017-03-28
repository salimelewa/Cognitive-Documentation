<!-- 
NavPath: Computer Vision API
LinkLabel: Frequently Asked Questions
Url: Computer-Vision-API/FAQ
Weight: 50
-->

# Computer Vision API Frequently Asked Questions
### If you can't find answers to your questions in this FAQ, try asking the Computer Vision API community on [StackOverflow](https://stackoverflow.com/questions/tagged/project-oxford+or+microsoft-cognitive) or contact [Help and Support on UserVoice](https://cognitive.uservoice.com/) 

## General Computer Vision API Frequently Asked Questions

**Question**: *Can I train Computer Vision API to use custom tags.  For example, I would like to feed in pictures of cat breeds to 'train' the AI, then receive the breed value on an AI request.*

**Answer**: This function is currently not available, however our engineers are working to bring this functionality to Computer Vision.

-----

**Question**: *Can Computer Vision be used locally without an internet connection?*

**Answer**: We currently do not offer a on premise or local solution.

-----

**Question**: *Which languages are supported with Computer Vision?*

**Answer**:
Supported languages include:

| | | Supported Languages | | |
|---------------- |------------------ |------------------ |--------------------------- |-------------------- 
| Danish (da-DK)  | Dutch (nl-NL)     | English           | Finnish (fi-FI)            |French (fr-FR)
| German (de-DE)  | Greek (el-GR)     | Hungarian (hu-HU) | Italian (it-IT)            | Japanese (ja-JP)
| Korean (ko-KR)  | Norwegian (nb-NO) | Polish (pl-PL)    | Portuguese (pt-BR) (pt-PT) | Russian (ru-RU)
| Spanish (es-ES)	| Swedish (sv-SV)	  | Turkish (tr-TU)   |                            |

-----

**Question**: *Can Computer Vision be used to read license plates?* 

**Answer**: The Vision API offers good text-detection with OCR, but it is not currently optimized for license plates. We are constantly trying to improve our services and have added OCR for auto license plate recognition to our list of feature requests.

-----

## Landmark Computer Vision API Frequently Asked Questions

**Question**: *How many landmarks does the model recognize?*

**Answer**: Approximately 9,000 landmarks

-----

**Question**: *What kind of landmarks are recognized?* 

**Answer**: We recognize both natural and man-made popular landmarks around the world.

-----

**Question**: *How did you select your landmarks?*

**Answer**: We used the Bing Satori graph to select popular landmarks from around the world.

-----

**Question**: *How good is your algorithm?*

**Answer**: We prioritized precision over recall for this model. We sacrificed knowing all popular landmarks in the world to identify our chosen landmarks correctly.

-----

**Question**: *I don’t get correct results in my image. Now what?*

**Answer**: Send us feedback using the UserVoice forum. We look forward to hearing feedback, and we use it to continue the improvement of our algorithms.

-----
