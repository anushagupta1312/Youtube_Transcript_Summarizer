<h1 style="color: #ff7f50;">Youtube_Transcript_Summarizer</h1>

<p>A project for developing a Chrome Extension that will send requests to a backend REST API for automatically summarizing video recordings using cutting-edge NLP techniques for abstractive text summarization.</p>

<h2 style="color: #ff7f50;">Table of Contents</h2>

<ul>
  <li><a href="#introduction" style="color: #008080;">Introduction</a></li>
  <li><a href="#features" style="color: #008080;">Features</a></li>
  <li><a href="#screenshots" style="color: #008080;">Screenshots</a></li>
</ul>

<h2 id="introduction" style="color: #ff7f50;">Introduction</h2>

<p>In today's digital age, an enormous amount of video recordings are made and shared online. However, finding the time to watch lengthy videos can be extremely challenging. Moreover, if we fail to extract any valuable information from these videos, our efforts may go in vain. This is where automatic video summarization comes into play.</p>

<p>The Automatic Video Summarization project aims to save time and effort by automatically generating concise summaries of video recordings. Leveraging cutting-edge Natural Language Processing (NLP) techniques for abstractive text summarization, this project allows users to quickly identify key themes and extract useful information from videos without having to watch the entire content.</p>

<p>This project presents a fantastic opportunity to put advanced NLP techniques into practice. It is particularly well-suited for intermediate developers seeking to enhance their NLP skills and gain hands-on experience. Additionally, it can serve as a revitalizing side project for professionals looking to explore new avenues in the field of video analysis and summarization.</p>

<h2 id="features" style="color: #ff7f50;">Features</h2>

<ul>
  <li>Automatic summarization of video recordings</li>
  <li>Implementation of cutting-edge NLP techniques for abstractive text summarization</li>
  <li>Time-saving and efficient way to extract key themes and information from videos</li>
  <li>Ideal for intermediates looking to put NLP techniques into practice</li>
  <li>Engaging side project for professionals in the field</li>
</ul>

## Approach

1. Using a Python API, find the transcripts and subtitles for a particular YouTube video ID.
2. Using the HuggingFace transformers, do text summarization on the acquired transcripts.
3. Provide a REST API for the Flask backend so that clients may access the summarising service.
4. Create a Chrome extension that uses the backend API to show users a text summary.

<h2 id="screenshots" style="color: #ff7f50;">Screenshots</h2>

<p>Project's output or user interface:</p>


![Screenshot (736)](https://github.com/anushagupta1312/Youtube_Transcript_Summarizer/assets/65394574/ff1725ca-2ba9-431e-809a-1f3bf12f8f14)

![Screenshot (737)](https://github.com/anushagupta1312/Youtube_Transcript_Summarizer/assets/65394574/c4f73804-3381-4f9d-b835-0719ede5e003)
![Screenshot (735)](https://github.com/anushagupta1312/Youtube_Transcript_Summarizer/assets/65394574/4374c10d-9c2a-4527-b8fc-85158a9a286e)
