<h1>Final Project - Systems Programming</h1>
Personal Assistant, called "May", using the micro controller esp32. This project integrating certain peripherals, such as speaker, amplifier, mic, and buttons. This system requier 2 esp32.
One esp23 is responsible of the Speach to Text and generation of response through API calls. The other esp32 is used for Text to Speech, which is done through API calls. 
We used Google TTS, Google STT, and OpenAPI to made this system work. We also created our 2 APIs to generate a response that is not verbose(Technology Used: NGINX. Flask, Gunicorn). 
One of the API is responsible of returning a new thread, and the other API is responsble for returning a response based on a passed question and thread arguments.
