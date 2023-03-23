# Youtube_Transcript_Summarizer

 ![image] (https://user-images.githubusercontent.com/65394574/170121667-49478981-6cbf-4d10-814f-7ca05db64c3d.png)

## Objective

In this project, we will develop a Chrome Extension that will send requests to a backend REST API, perform NLP, and return a condensed transcript of a YouTube video.


## Purpose of the Project

Throughout the day, a tremendous amount of video recordings are made and shared online. The task of devoting time to watching videos that may be longer than anticipated has become extremely challenging, and if we fail to glean any useful information from them, our efforts may be in vain. Such videos can be summarised automatically, which saves us time and effort by allowing us to rapidly scan for key themes without having to watch the entire thing again.
This project will provide us the chance to put cutting-edge NLP technique for abstractive text summarization into practise while also implementing an intriguing notion that is ideal for intermediates and a revitalising side project for pros.


## Approach

1. Using a Python API, find the transcripts and subtitles for a particular YouTube video ID.
2. Using the HuggingFace transformers, do text summarization on the acquired transcripts.
3. Provide a REST API for the Flask backend so that clients may access the summarising service.
4. Create a Chrome extension that uses the backend API to show users a text summary.
