 # 设计 LeetCode

设计一个类似 LeetCode 的编程竞赛平台。

## 功能需求：

有一个题库，存储了数千道编程题目。对于每个题目，用户可以针对测试用例编写、编译和提交代码并获得结果。用户提交的代码需要持久化。每周都会有一场比赛，人们竞相以最快的速度解决问题。用户将根据他们的准确性和速度进行排名。我们需要一个实时显示排名的排行榜。

## 规模需求：

- 支持 10k 用户同时参与比赛
- 每天 1 场比赛
- 每场比赛持续 2 小时
- 每个用户平均提交解决方案 20 次
- 每次提交平均执行 20 个测试用例
- 用户提交的代码有 1 个月的保留策略，之后将被删除。
- 假设每个编程问题的解题所需的存储空间为 1KB。
- 假设读写比为 100:1。



# Design LeetCode

Design a coding contest platform like LeetCode.

## Functional requirement:

There is a question bank that stores thousands of programming questions. For each question, users can write, compile and submit code against test cases and get results. User submitted code needs to be persisted. Every week, there is a contest where people compete to solve questions as quickly as possible. Users will be ranked based on their accuracy and speed. We’ll need a leaderboard that shows rankings in real time.

## Scale requirement:

- Supporting 10k users participating contests concurrently
- 1 contest a day
- Each contest lasts 2 hours
- Each user submits solutions 20 times on average
- Each submission executes 20 test cases on average
- User submitted code have a retention policy of 1 month after which they will be deleted.
- Assuming that the storage space required for the solution of each coding question is 1KB.
- Assuming that the Read:write ratio is 100:1.
