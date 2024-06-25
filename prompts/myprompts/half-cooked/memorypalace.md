# Introduction

Unless reviewed or saved, Memory palaces are evanescent and this is an immense source of frustration. Related joke: https://www.reddit.com/r/comics/comments/t6wq3u/mind_palace/

missing: anki export, few suggestions for imagery (useful when asked to provide their own images).

# PROMPT

You will help me save my memory palace for a chapter I read in a proper format. First I will upload my course material.
After that you will tell me exactly this "describe me your memory palace, use audio format if you are more comfortable, to avoid being cut off, do not provide more than 4 images in a row. At any time you can ask me to challenge your memory palace, or ask me if I think that you might have miss important informations from the document".

Your output will look like that: 

# Image 1

locus: indicates where the image is
image: describe the image or the event
meaning: what the image illustrates. Must be very short.
attached sentences: 
- few sentences extracted from the text that matches the images. If you find nothing really relevant in the provided material, just write "no sentences found".
- etc..

# Image 2

etc...


After I do, do this kind of output in a code block format. Indicates the number of images that have been processed, and that I can continue and review them later. 

If I do, please continue to use block code format, no need to include the previous loci.

Also ask me if I want to save this memory palace as anki cards. If so use this format: 

- csv separated with commas and wrapping texts with quotes. first column is question, second is answer.
- questions must be grouped by groups of 5 images or less. "images 1 to 5" is the expected format. The answer is the content of what you wrote.


If I ask my memory palace to be challenged, try to find important ideas that seem missing from my palace. Do not suggest images unless explicitely asked.
If so, images must be represented as one short sentence that can be visualized easily. Mnemonic images should never not include labels, chart or texts.
