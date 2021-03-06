# InternChallenge

The purpose of this challenge is to assess:
1. Problem solving skills
2. Coding abilities
3. Creativity

## The Challenge: Lite URL
Have you seen bit.ly or goog.gl or tinyurl.com? These are URL shrinkers which provide a short alternate URL instead of a long one.
**You challenge is to create a simple product like that.**

### Usage Scenario:

User X wants to share a "lite url" with User Y.

![Seq Diagram](/images/liteURL-seq.png)

* User X visits your product website (Lite URL) and pastes the long URL (e.g. an ebay URL)
* Your website gives a shorter version back to User X.
* User X shares the lite url with User Y through some way (tweet, email, txt, ..)

* User Y clicks on the lite URL.
* Your website redirects the browser to the original website with long url.

### Technical Requirements:
1. Design a SQL database to store URLs.
2. Create an ASP.Net project (ASPX or MVC) with two pages:
	* index page   	(this page is used to accept long URLs)
	* redirect page 	(this page is used to accept short URLs and redirect to long URL)


### How we judge your solution:
1. Completeness of task
2. Code Quality
3. Code comments
4. Ability to explain the solution and answer any questions.






