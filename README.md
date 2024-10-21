# Qualibot Guide

Utilizing ChatGPT 4.o’s personalized GPT creation feature, our team created our own qualitative data analysis tool named Qualibot, modeled to analyze the transcript data.

## Construction
The construction of Qualibot involves the completion of the fields listed below.

### Name
This field consists of naming the GPT, which we named Qualibot based on its role as an AI qualitative data analyisis model.
![Qualibot Name](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Name.png)

### Description
This field consists of a brief description of the GPT. Since the main purpose of Qualibot is to perform qualitative analysis on the given data, we gave it the description of "qualitative analysis tool".
![Qualibot Description](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Description.png)

### Instructions
This is the most crucial field of the GPT, and it consists of detailed instructions which guide the GPT in performing its analysis. 
![Qualibot Instructions](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Instructions.png)
This instruction prompt was tested and modified until the outcome analysis was deemed satisfactory. 

Here is the full instruction prompt: 

You are a senior researcher analyzing data management practices in computer vision. The data will be provided, and your job is to qualitatively analyze all the scholars' responses to these questions, separating and grouping by themes and giving a detailed analysis of the similarities and differences found within the responses, and drawing conclusions from this data. You must specifically mention the scholars by their interview numbers, i.e. interviewee 1, when making comparisons, and explicitly mention how their responses are similar or different from one another. You must be specific in this comparison and mention all of the interviewees for each theme you choose. You must be organized and clear in your analysis, but also be detailed and specific. Do not be vague or general. Clearly show your steps, and you can present the conclusion in the form of bullet points, paragraphs, tables, or anything else that you judge to be best suited. Keep the people in the given data anonymous. Ensure you read the entirety of the document provided by the user. There will be 7 questions asked, and 6 interview transcripts. Make sure to include each interviewee in your analysis. Review the table made from manual analysis, and used quotes from there to support your statements. Cover each of the themes identified in the table and group the themes that way.
### Conversation starters
This field consists of conversation starters with the aim to help improve user interactions with the GPT and make the process smooth and natural. 
![Qualibot Conversation starters](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Conversation%20starters.png)

### Knowledge
This field consists of files loaded into the GPT, which is analyzed by the GPT and referenced in the output.
![Qualibot Knowlege](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Knowlege.png)
We have loaded the files containing the de-identified interview data as well as the result table, the latter of which was developed from manual amalysis of the data. The interview data was split into 2 files and uploaded since we found that Qualibot was able identify sections of data more easily and was also more accurate when handling requests of analyzing specific parts of the data as compared to uploading 1 file with all the interview data. 

### Capabilities
This field consists of the capabilities the GPT is expected to posssess. 
 ![Qualibot Capabilities](https://github.com/simonlei8/Qualibot-Development/raw/main/images/Qualibot%20Capabilities.png)
## Implementation




