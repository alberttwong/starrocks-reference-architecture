### What is a Performance Model

Performance modeling is a structured and repeatable approach to modeling the performance of your software. It's both an information structure and a process to help you capture performance-related information, including performance threats. When you create performance models, you identify application scenarios and your performance objectives. Your performance objectives are your measurable criteria, such as response time, throughput (how much work in how much time), and resource utilization (CPU, memory, disk I/O, and network I/O). You break down your performance scenarios into steps and assign performance budgets. Your budget defines the resources and constraints across your performance objectives. You can use performance modeling to shape your application's design to meet your performance objectives, and reduce risk. https://www.guidanceshare.com/wiki/How_To:_Create_a_Performance_Model_for_a_Web_Application


### Current Strategy

Organizations are moving to an APM based monitoring model and a horizontal scaling capacity model with a focus on the end user experience.

### kube-monkey
is an implementation of Netflix's Chaos Monkey for Kubernetes clusters. It randomly deletes Kubernetes pods in the cluster encouraging and validating the development of failure-resilient services.
https://github.com/asobti/kube-monkey

### JMeter or Gattling
Why?  Performance as code.  https://saucelabs.com/blog/ask-a-selenium-expert-should-i-test-load-with-selenium

### CNCF Jaeger and zipkin
It provides distributed context propagation, distributed transaction monitoring, root cause analysis, service dependency analysis, and performance / latency optimization.
http://opentracing.io/documentation/pages/supported-tracers
