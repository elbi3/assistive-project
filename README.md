# title

## project architecture

https://www.figma.com/board/Cxyqbenf3BaFexlc0ShScS/Untitled?node-id=2-1989&t=28EJR1aGsF4wZP7F-0

## application flow
barcode scan --> fetch ingredients & nutrition data --> run deterministic assessment logic --> send results to LLM with prompt for ingredient classification --> compute food score --> generate explanation with second AI call

## ai use
- ingredient classification
- ingredient text cleaning
- explanation generation

## data handling

- deterministic logic
- selective AI handling

## technologies
1. barcode scanner
https://www.npmjs.com/package/html5-qrcode
2. Streamlit or Vue.js front-end & NativeScript-Vue mobile application
https://nativescript-vue.org/
3. Python: Request library
4. HuggingFace API

## application expansion
- add pattern detection and learning to improve scoring
- add personalization 
- add company and manufacturer data. include news articles, studies, and other available public information

## additional questions
How to handle food without a barcode? an apple?


