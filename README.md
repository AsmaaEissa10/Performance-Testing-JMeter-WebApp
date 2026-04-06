<p align="center">
  <img src="https://jmeter.apache.org/images/jmeter.png" width="700" style="background-color:white; padding:10px; border-radius:10px;"/>
</p>

🚀 𝗘𝗻𝗱-𝘁𝗼-𝗘𝗻𝗱 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲 𝗧𝗲𝘀𝘁𝗶𝗻𝗴 𝘂𝘀𝗶𝗻𝗴 𝗝𝗠𝗲𝘁𝗲𝗿 𝗳𝗼𝗿 𝗪𝗲𝗯 𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻

I recently worked on a practical performance testing project using Apache JMeter,
where I tested a real user journey on an e-commerce website.
 
🔹Base URL: https://www.demoblaze.com/

🔹 𝑻𝒆𝒔𝒕 𝑷𝒍𝒂𝒏 / 𝑼𝒔𝒆𝒓 𝑭𝒍𝒐𝒘

* Open Home Page
* Sign Up
* Login
* Select Category
* Select Product
* Add to Cart
* View Cart
* Place Order
* Logout

🔹 𝑱𝑴𝒆𝒕𝒆𝒓 𝑻𝒆𝒔𝒕𝒊𝒏𝒈 𝑻𝒆𝒄𝒉𝒏𝒊𝒒𝒖𝒆𝒔

* Data-driven testing using CSV Data Set Config (multiple users & inputs)
* Handled dynamic data (session IDs, tokens) using Regular Expression Extractor
* Improved structure and reusability using Test Fragments
* Recorded the full user journey using HTTP(S) Test Script Recorder

🔹 𝑼𝒔𝒆𝒓 𝑩𝒆𝒉𝒂𝒗𝒊𝒐𝒓 𝑺𝒊𝒎𝒖𝒍𝒂𝒕𝒊𝒐𝒏

* Uniform Random Timer – adds realistic delays between requests
* Loop Controller – repeats requests to simulate load
* Executed tests in GUI mode for debugging and monitoring

🔹 𝑹𝒆𝒑𝒐𝒓𝒕𝒊𝒏𝒈 & 𝑨𝒏𝒂𝒍𝒚𝒔𝒊𝒔

* View Results Tree – validated individual request responses
* Summary Report – reviewed response time and error rate
* Aggregate Report – analyzed performance trends
* Generated a detailed HTML report for clear visualization

🔹 𝑽𝒂𝒍𝒊𝒅𝒂𝒕𝒊𝒐𝒏 & 𝑭𝒊𝒏𝒅𝒊𝒏𝒈𝒔

* Validated results against acceptance criteria (response time, error rate, throughput)
* Identified failing requests
* Reported issues to the development team for fixes

