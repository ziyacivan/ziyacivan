## Yusuf Ziya CIVAN
Hi. I am Ziya, a Software Developer from Isparta, Turkey. I am currently working at Akinon. I usually work as a Backend-Focused Software Developer. I have 2+ years of experience in high-scale and high-traffic products. I worked on different projects before, like an Ethereum network-based social media platform, an algorithmic trade bot, an embedded system for the Turkish Highway Authority, and I am currently working on the Omnitron project in my current company. Omnitron is an operational centre for managing all digital commerce business needs, such as channels, product information, content management, prices & inventory, promotions, and more.

I usually use these technologies like Python, Django, DRF, and PostgreSQL, for REST Api projects, but I have experience in Frontend fundamentals as well.

## Recent Work History
I am working 2+ years at Akinon. I develop roadmap features, analyzing how we can implement new features into our current business logics.

**Core responsibilities**:
- Developing roadmap features (We're getting +100 tasks from the roadmap every year for each developer on my team)
- Responsibility of refactoring legacy code and business logic.
- Improving test coverage rate for each module (We have 30+ project packages in our project)
- Core responsibility of Channel-App library (I am working on this library alone)
   - When a marketplace wants to send any product from one marketplace to another marketplace, it should create a sales channel and must use this library. The library works like an SDK (like ShopifySDK).
 
**Core completed features**:
- Asynchronous support for async payment and refund transactions. Some banks or payment gateways work asynchronously for payments and refund transactions. Omnitron had no asynchronous support for these processes.
- Multi-cancellation support for the same time. Omnitron had been able to get one cancellation request same time and process the cancellation when the cancellation is complete. I developed a multi-cancellation support for the cancellation logic. When a customer activates multi-cancellation support with a feature flag, the order owner can send multiple cancellation requests same time for the same order.
- Optimizing filter operations. Omnitrons had most filters that make N+1 issues when filtering. I had detected all of N+1 issues when filtering with HTTP requests and fixed all of them for each filter class.
- Developing log and monitor screens with React and FastAPI for the Channel App library. This feature works like VSCode editor breakpoints. Simulates manual breakpoints and debug operations, but automatically.
