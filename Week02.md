# Week 2 實習心得 Internship Blog
## 主要學習內容 Main Learning Target: Unit Testing 單元測試
### 為什麼需要做單元測試？Why we need to write "Unit Testing"?
因為在進行端對端的整合時需要花費大量的成本，所以會在每個小單元進行一次單元測試，測試的目的是在確保每個小單元都能夠正常的運作。
如此一來，最後在進行端對端的整合時會省下很多時間，也可以提高成功率，這是一個投入最小而且最快的方式。
所以在這周主要都是在進行後端各項功能的單元測試。

Due to the high costs associated with end-to-end integration, unit tests will be conducted on each individual module. The purpose of these tests is to ensure that each module functions correctly. By doing so, significant time will be saved during the final end-to-end integration, and the success rate will be improved. This approach is the most efficient and cost-effective way to proceed. Therefore, this week will primarily focus on conducting unit tests for various backend functionalities.

#### 專有名詞解釋 Explanation
1. **_整合測試 Integration Testing_** : 整合多方資源進行測試，確保模組與模組之間的互動行為正確無誤，也讓不同模組在各自開發維護的過程中不會因為功能調整而遭到破壞。 Integrating multiple resources for testing ensures that the interactions between modules are accurate and error-free. This approach also prevents any disruption or damage to different modules during their respective development and maintenance processes due to functional adjustments.
2.  **_端對端測試 End-to-end Testing ( E2E Testing )_**: 是指從使用者的角度出發，對真實系統進行測試。From the user's perspective, it refers to testing the real system.

### 單元測試的注意事項？Limitation of "Unit Testing"?
1. **_不可以與真實世界有互動（API, DB）_** Do not have the connection with real web during the unit testing
2. **_專住在單元本身_** Focus on the "Unit", not other related functions
3. **_測試的覆蓋率不需達到100%_** 100% successful is not needed
