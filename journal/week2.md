# Week 2 — Distributed Tracing

## Requirements
This week we worked on instrumenting observability tools. The tools used this week were AWS Xray, Honeycomb and Rollbar.
I was definitely not familiar with these tools as the organizations I have worked with were more interesed in logs and filtering data from there. I am definitely going to have to explore this more.

### HoneyComb
Honeycomb uses the OpenTelemetry APIs, libraries to "speak" to various applications. OpenTelementry is an open-source industry standard for gathering data.

We built a dataset in Honeycomb for the backend application. This allowed us to see the spans/traces from the application.

![honeycomb img1](/journal/img/honeycomb1.png)

We also built queries to pull out data and to look a specific metrics.

![honeycomb img2](/journal/img/honeycomb2.png)

### AWS X-Ray
Implmented XRay in order to become familiar with this tools approach to obervability. The Xray trace group and entered the criteria for the data sampling  with the AWS CLI. After implementing, I commentted out the code to limit spend. Along wth this we also setup CloudWatch to gather logs.

![xray img2](/journal/img/xray2.png)

![xray cv](/journal/img/xray%20cw%20logs.png)

### Rollbar
This was the final tool implemented to track errors. It was simliar to Honeycomb in its ease to set up.

![rollbar img1](/journal/img/rollbar1.png)

![rollbar img2](/journal/img/rollbar2.png)

