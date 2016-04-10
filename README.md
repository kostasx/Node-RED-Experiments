# Node-RED-Experiments
Experimenting with Node-RED

### Image Analysis

**Description:**

Node-red flow that analyses an image to find faces and then draws a colored rectangle around each face detected. If a person is identified, his name is also displayed next to the rectangle.

The image URL is entered via a GET request query parameter: http://mybluemix.net/image?url=http://domain.com/image.jpg

**Dependencies:** Alchemy Image Analysis Node

[Node-RED flow](http://flows.nodered.org/flow/7bc0b97f3de6c1bc9a57f7426fdee2c8) | [Gist](https://gist.github.com/kostasx/7bc0b97f3de6c1bc9a57f7426fdee2c8)

**Samples:**

![Alt text](/image-analysis/img/node-red-image-analysis-hollywood.png)
![Alt text](/image-analysis/img/node-red-image-analysis-ryan-gosling.png)
![Alt text](/image-analysis/img/node-red-image-analysis-steve-martin.png)

