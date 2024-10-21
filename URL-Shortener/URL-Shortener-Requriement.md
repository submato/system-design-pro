- # 设计 URL 缩短器

  设计一个类似 bit.ly 的 URL 缩短器服务

  功能要求：

  - URL 缩短：给定一个 URL，服务应生成一个更短且唯一的别名。这是服务的核心功能。缩短的 URL 在所有用户中应该是唯一的。缩短的 URL 应尽可能短，以节省字符，仅使用英文字母（a-z、A-Z）和数字（0-9）。
  - URL 重定向：如果用户访问缩短的 URL，服务应将其重定向到原始 URL。
  - 分析：服务应能够跟踪短链接的访问次数。

  规模要求：

  - 1 亿日活跃用户
  - 读写比 = 100: 1
  - 数据保留 5 年
  - 假设每天有 100 万次写入请求
  - 假设每个条目约为 500 字节

# Design Url Shortener

Design a Url Shortener service like bit.ly

Functional requirement:

- URL Shortening: Given a URL, the service should generate a shorter and unique alias of it. This is the core functionality of the service. The shortened URL should be unique across all users. The shortened URL should be as short as possible to save characters using only English alphabet letters (a-z, A-Z) and digits (0-9).
- URL Redirection: If a user accesses a shortened URL, the service should redirect them to the original URL.
- Analytics: The service should be able to keep track of the number of times a short link has been accessed.

Scale requirement:

- 100M Daily Active Users
- Read:write ratio = 100: 1
- Data retention for 5 years
- Assuming 1 million write requests per day
- Assuming each entry is about 500 bytes