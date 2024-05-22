# Google-XSS-Game

Game Available at https://xss-game.appspot.com/

<h2>Level 1</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/bbc2d5fa-2662-4157-800e-cb2820942a05">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/8c6c6029-280a-46d8-becd-a6a8cda3483e">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/e7501a3d-a14e-4cb1-9380-cc6326d0df58">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/16cb0b6f-cc1c-41f4-be53-501acfcda992">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/4d0d099e-e0d6-4926-92e0-ebae0f393a1c">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/f9adaafc-44aa-49f4-8398-2cd962b7c37a">
</p>

<br>

The goal of Level 1 is to trigger a pop-up JavaScript alert() within the frame. This can be achieved using a reflected cross-site scripting (XSS) attack. When you click the search button, a results page appears, with the query reflected in the URL. Using Google Chrome Developer Tools, you can see that there is no data sanitization on the search query input. This lack of sanitization allows you to inject a script tag with an alert function, successfully executing the XSS attack.

<br>

<h2>Level 2</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/6ff37456-bc12-4f2c-92e8-eebbfe36fae1">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/7bdf5be3-d67d-4d98-adb3-bcb4736f8d0e">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/288ca868-3e94-45d9-bbde-3be151fe4d56">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/acb35f54-62a0-4a04-862d-221fba17a635">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/f5787cf9-3e05-4431-b723-342493a8c876">
</p>

<br>

The goal of Level 2 is to trigger a pop-up JavaScript alert() within the frame. This can be achieved using an img tag with an onerror attribute. When you click the "Share Status!" button, the post undergoes data sanitization, which removes any script tags. Therefore, an img tag with the onerror attribute is another way to trigger the alert.

<br>

<h2>Level 3</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/e73e8372-a1a3-4117-b77f-7ccd1d77a700">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/6268d901-8519-48fe-8650-32089f981a32">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/6f8c90ab-2ca9-4c28-ac9b-52ce28de0030">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/20388d76-d824-4002-9c8f-2b35054e70d8">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/d927ef0c-902d-48df-bb77-58af441cb283">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/edcfefc1-cce7-4895-81c0-4ba522d77de4">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/b5e7e8f8-78dc-4807-9a67-e9f5d80d81ac">
</p>

<br>

The goal of Level 3 is to trigger a JavaScript alert() pop-up within the frame. This can be achieved by manually editing the URL in the address bar. The behavior of the URL changes based on the selected image. If a number outside of 1, 2, or 3 is entered, a blank screen appears. If any text other than an integer is input, "Image NaN" is returned. Therefore, the only way to inject a script is by using an apostrophe (') after the pound (#) symbol. Injecting a script tag won't work, so another way to trigger an alert is by using the onerror attribute.

<br>

<h2>Level 4</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/37dcfb2a-3536-4694-8687-26de5c1e4893">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/37db782b-7591-4935-b080-c33285401ee8">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/70977b39-2aac-4b43-a29f-32a61c2eab09">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/93d32e76-747c-4cfc-a93a-0e1905aaecc6">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/6bd80389-e8df-4c69-a75a-2226ac9c095c">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/db2b98b0-8409-48fd-918a-0391ece77afa">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/13fca794-64a1-42e2-ab4d-01f717e6ca2b">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/50c2b83c-1bc6-405a-a26b-38ddc553a872">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/b851421a-9600-4d06-87cb-eec97b1ceaba">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/d3fbb879-ad96-4c94-bfd2-d7d24d39597d">
</p>

<br>

The goal of Level 4 is to trigger a JavaScript alert() in the application. This can be achieved by observing the Google Chrome Developer Tools network tab. Every time a timer is created, a GET request is initiated, followed by a loading screen. Once the timer is finished, the "Create Timer" window appears. An apostrophe won't work due to HTML encoding, but parentheses and semicolons do work. Therefore, an alert script can be constructed and triggered by progressively testing which characters are HTML encoded.

<br>

<h2>Level 5</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/2d1a5102-e403-4e08-a88c-c92c6dc9a0a8">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/3f11ccf6-a7dc-45c7-9fc9-ab0e0514c162">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/333a0322-9f3a-4c62-b580-696c9f631c77">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/4730b3ae-6a23-489b-a1b9-c405e3193931">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/72b0bc31-9959-40b8-a4d8-78fa3c420f85">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/901f07fa-79a2-448a-bf9a-255fb75cae18">
</p>

<br>

<h2>Level 6</h2>

<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/e782f4a1-09a8-4e0c-8bff-aba6d6313a7b">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/da5c26b0-9b96-4300-8f16-2105841613fd">
</p>
<p align="center">
  <img src="https://github.com/bensadel/Google-XSS-Game/assets/95494769/1a0de95f-37ee-4304-9e0c-c479a8d9cbb6">
</p>



