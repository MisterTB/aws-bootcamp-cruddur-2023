# Week 2 — Distributed Tracing

## Requirements
This week we worked on instrumenting observability tools. The tools used this week were AWS Xray, Honeycomb and Rollbar.
I was definitely not familiar with these tools as the organizations I have worked with were more interesed in logs and filtering data from there. I am definitely going to have to explore this more.

### HoneyComb
Honeycomb uses the OpenTelemetry APIs, libraries to "speak" to various applications. Opentelementry is a open-source industry standard for gathering data.

We built a dataset in Honeycomb for the backend application. This allowed us to see the spans/traces from the application.
pic1

We also built queries to pull out data and to look a specific metrics.
pic2

### AWS X-Ray
Implmented XRay in order to become familiar with this tools approach to obervability. The Xray trace group and entered the criteria for the data sampling  with the AWS CLI. After implementing, I commentted out the code to limit spend. Along wth this we also setup CloudWatch to gather logs.
pic1

### Rollbar
This was the final tool implemented to track errors. It was simliar to Honeycomb in its ease to set up.

pic1/2

