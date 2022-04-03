# Lightstreamer

Here I have implemented a simple demo with Lightstreamer server version 7.2.2 for single channel masseging.
Here I am combining two  below example in a single page. 

1. Lightstreamer - Stock-List Demos with Web Push Notifications - HTML Clients
2. Lightstreamer - Market Depth Demo - HTML Client

## Installation

1. Download Lightstreamer:

Please download from here <a href="http://www.lightstreamer.com" rel="nofollow">Lightstreamer</a>
Then unzip and keep all in a single folder. The server-side part of this demo, the Metadata and Data Adapters, is covered in this project: Lightstreamer - Market Depth Demo - Java Adapter.

2. Clone this repository: 

```
git clone git@github.com:devnet-limited/hrms.git
```

3. Run Lightstreamer Server:

On comandline, enter to your server script folder and dig to bin/unix-like and run the below cmd. But do not run this cmd first. You will run this cmd after completing the other steps first. Here I am using 8080 and 8888 port to run Lightstreamer server. To run clinet script I am using 8003, 8002, 8001 port.

```
./start.sh 
```
or 

```
./LS.sh run
```

4. Remote adapter: 

The server-side part of this demo, the Metadata and Data Adapters, is covered in this project: Lightstreamer - Market Depth Demo - Java Adapter.


5. Client Side:

Copy client-project folder with all files to Lightstreamer/pages/demos/client-project or to your external web server location as you need.

Also copy the files, env.js, firebase-messaging-sw.js, manifest.json to the root folder or Lightstreamer/pages/Here . 

6. Browse client:
Now go to your faverite browser and browse https://localhost:8080/demos/client-project or url of your web server.



## References

* Lightstreamer: https://lightstreamer.com/static/download/
* Lightstreamer Documentation: https://libraries.io/pypi/lightstreamer-adapter
* Lightstreamer Demos: https://demos.lightstreamer.com/
* Lightstreamer - Market Depth Demo - HTML Client: https://github.com/Lightstreamer/Lightstreamer-example-MarketDepth-client-javascript
* Lightstreamer - Stock-List Demos with Web Push Notifications - HTML Clients: https://github.com/Lightstreamer/Lightstreamer-example-MPNStockList-client-javascript