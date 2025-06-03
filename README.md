🚀 Tawk App – API Load Testing Report

👉 Watch Full Load Test on link

📋 Overview
This project includes API Load Testing for the Tawk App using simulated user traffic. The primary goal was to evaluate how the app handles high-volume requests with different ramp-up times and ensure performance remains stable under heavy load.

🧪 Test Details Recap
Total Users: 2,500 👥

Requests per User: 3 (Total ~7,500 Requests)

Ramp-up Times Tested:

500ms

250ms

150ms

50ms

1 Second

🔍 Observations
✅ All ramp-up tests passed successfully, except the 1-second ramp-up test.

❌ 1-second ramp-up failed, indicating the system may not efficiently handle slower ramp-up speeds with the same load.

⚠️ Shorter ramp-up intervals (like 50ms) still passed, showing better scalability under rapid user injections.

🧠 Analysis
The system performs better when users are ramped up quickly.

A slower ramp-up time like 1s/user might keep connections open longer or cause session delays, leading to test failure.

High concurrency handling is strong under rapid bursts.

🛠️ Tools Used
Load Testing Tool: (JMeter )

Environment: Staging

API Endpoint: (Insert endpoint or base URL here)

Monitoring: Logs, response times, error tracking
