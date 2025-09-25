# Amazon Performance Testing with JMeter

This repository contains an **automation performance testing project** conducted on [Amazon](https://www.amazon.com/) using **Apache JMeter**.  
The objective was to simulate concurrent users accessing the site and analyze performance metrics such as response time, throughput, and error percentage.

---

## 📋 Overview
- Tool Used: **Apache JMeter**
- Protocol: **HTTP GET Requests**
- Target Site: [Amazon](https://www.amazon.com/)
- Test Scenario: **10 concurrent virtual users**

---

## 📊 Test Results (Sample Run)
- **Total Samples:** 10  
- **Average Response Time:** 0 ms (requests failed due to malformed URL setup in JMeter)  
- **Error %:** 100% (indicating incorrect configuration / unsupported protocol in request sampler)  
- **Throughput:** ~11.08/sec  
- **Avg. Bytes:** 863  

> The report highlighted a **MalformedURLException: unknown protocol: https:** error, showing that the HTTPS protocol wasn’t correctly configured in JMeter.  

---

## ⚙️ How to Run
1. Install [Apache JMeter](https://jmeter.apache.org/).  
2. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/amazon-performance-jmeter.git
   cd amazon-performance-jmeter
