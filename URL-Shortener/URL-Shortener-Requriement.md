# URL Shortener System Design

## Functional Requirements

- URL Shortening: Given a URL, the service should generate a shorter and unique alias of it. This is the core functionality of the service. The shortened URL should be unique across all users. The shortened URL should be as short as possible to save characters using only the English alphabet letters (a-z, A-Z) and digits (0-9).
- URL Redirection: If a user accesses a shortened URL, the service should redirect them to the original URL.
- Analytics: The service should be able to keep track of the number of times a short link has been accessed.

## Nonfunctional Requirements

Scale requirements:

- 100M Daily Active Users
- Read:write ratio = 100: 1
- Data retention for 5 years

Other requirements:

- High availability
- Low latency
- High durability
- Security
