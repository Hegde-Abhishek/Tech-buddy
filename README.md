**TechBuddy**

Tech buddy web application is designed to be a social media platform that caters specifically to developers who want to learn, explore, connect and grow with other techies.
Users will have access to a range of features including analytics, challenges, quizzes, comments, and more, all designed to help them enhance their skills and knowledge.
Our analytics feature will provide developers with real-time data about their performance and progress, allowing them to monitor their growth and identify areas where they need to improve.
With our challenges feature, developers can put their skills to the test by completing challenges that are designed to motivate them.
Developers can interact with each other through our comments feature, allowing them to share ideas, ask questions, and provide feedback to one another.
Our platform will be easy to use, intuitive, and accessible from any device, ensuring that users can learn and grow wherever and whenever they want.

Overall, our goal is to create a vibrant and supportive community of developers who can learn from one another, share their knowledge, and work together to advance their skills and careers.
## Screenshots
Blog
![App Screenshot](https://rohancodes2.github.io/images/blog-feature.png)
Login
![App Screenshot](https://rohancodes2.github.io/images/Screenshot%202023-04-20%20at%2011.30.22%20AM.png)
Blog detail
![App Screenshot](https://rohancodes2.github.io/images/blog-detail.png)
Challenges
![App Screenshot](https://rohancodes2.github.io/images/challenges.png)
Analytics
![App Screenshot](https://rohancodes2.github.io/images/analytics.png)



## REST API resources required for the project user stories.

**For Developers**

GET  /developers - Retrieve a list of all developers

GET  /developers?developername=johndoe

POST  /developers - Create a new developer

GET  /developers/{developerId} - Retrieve a specific developer by ID

PUT  /developers/{developerId} - Update a specific developer by ID

DELETE  /developers/{developerId} - Delete a specific developer by ID


**For Posts**

GET /posts - Get all posts

GET /posts/{postId} - Get a specific post

POST /posts - Create a new post

PUT /posts/{postId} - Update an existing post

DELETE /posts/{postId} - Delete a post

POST /posts/{postId}/likes - Update Like

DELETE /posts/{postId}/likes - Delete Like

POST /posts/{postId}/comments - Update Comment

DELETE /posts/{postId}/comments - Delete Comment

POST /posts/{postId}/shares - Update Share

DELETE /posts/{postId}/shares - Delete Share


**For Bookmarks**

GET /bookmarks - This endpoint retrieves all the bookmarks in the system.
 
GET /bookmarks/{bookmarkId} - This endpoint retrieves a specific bookmark by its ID.

POST /bookmarks - This endpoint creates a new bookmark in the system.

DELETE /bookmarks/{bookmarkId} - This endpoint deletes a bookmark by its ID.

GET /bookmarks/search?q={query} - This endpoint searches for bookmarks based on a query string.



**For Analytics**

GET /analytics/{developerId} - Get the analytics



**For Challenges**

GET /challenges - Retrieve a list of all challenges

POST /challenges - Create a new challenge

GET /challenges/{challengeId} - Retrieve a specific challenge by ID

DELETE /challenges/{challengeId} - Delete a specific challenge by ID

PUT /challenges/{challangesId} - Update the challenge


**For Submissions**

GET /submissions/{developerId} - Get all submissions by particular Author

GET /submissions/{developerId} - Get all submissions of developer





![TECHBUDDYTDD](https://user-images.githubusercontent.com/122548499/227009755-50ebf098-05ae-4ca8-bdb9-e46b43a1cb97.jpg)




