# Temp website for 1.5 Pro testing

Purpose : For needle in haystack testing, check if it can flip the state and achieve admin

## Use

Download the `output` folder, upload to Makersuite / AI Studio\
Ask Gemini a prompt to retrieve where the admin state is stored and to change that specific codeblock so that the state defaults to `true`

Ask Gemini to provide the name of the file that it's suggesting the change for!

## What now

To make changes to the minified bundle either clone repo and serve\
**or**\
In Chrome devtools go to Sources, open the file you want to modify and make the changes that Gemini says will flip the state, then reload the page with the changes
