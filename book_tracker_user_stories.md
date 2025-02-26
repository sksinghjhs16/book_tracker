# Book Tracker User Story
## User Stories for Registration & Login
Application Registration: As a new user, I want to register by entering my name, email, and password so that I can track my reading progress.
Application Login: As a registered user, I want to log in using my email and password so that I can access my book list and progress.
Error Feedback on Signup & Login: As a user, I want to receive error messages if I enter incorrect details during signup or login so that I can correct them.
Store User Data: As a user, I want my login details to be stored securely so that I don’t have to log in every time I open the app.

Homepage Features

Welcome Message: As a user, I want a personalized greeting when I log in.
Current Book Progress: As a user, I want to see my ongoing book progress.
Completed Books: As a user, I want to view my finished books list.

Detail Screen User Stories

View Book Details: As a user, I want to view complete details of a book, including title, author, genre, and cover image, so that I can quickly access relevant information.
Track Reading Progress: As a user, I want to see my reading progress (percentage, pages read, start and finish dates) on the detail screen, so that I can monitor my progress easily.
Edit Reading Progress:  As a user, I want to update my reading progress manually (pages read or percentage completed) on the detail screen, so that I can track my progress accurately.
Add Personal Notes: As a user, I want to add and view personal notes for a book, so that I can jot down key insights or thoughts while reading.
Write & Edit Summary: As a user, I want to write and edit my book summary on the detail screen, so that I can save my understanding of the book.
Mark as Completed: As a user, I want to mark a book as completed directly from the detail screen, so that I can update my reading status quickly.
Delete Book Entry: As a user, I want to delete a book from my list via the detail screen, so that I can remove unwanted entries.
View Analytics for Book: As a user, I want to see reading time statistics and trends for a book on the detail screen, so that I can analyze my reading habits.



Persistent Data Integration

Login State Persistence: As a user, I want my login state to persist across sessions so that I don't need to re-enter details every time.
User Preferences Persistence: As a user, I want to save my preferences such as dark mode so that the app remembers my settings.
User Activity Logs Persistence: As an admin, I want user activity logs to persist so that I can track and analyze trends over time.

Integrate External API

External APIs enhance app functionality by allowing integration with third-party services, such as book metadata retrieval, AI-generated summaries, or progress syncing across platforms. These integrations make the app more dynamic and user-centric.

Fetch Book Details: As a user, I want to fetch book details (author, summary, genre) by entering the book's title so that I don’t have to manually input all information.
Example: The app integrates with an external book database API (e.g., Google Books API) to auto-fill book details when adding a new book.
Why: Saves time and ensures accurate book information.

AI-Generated Book Summaries: As a user, I want to generate an AI-powered summary of a book so that I can quickly review key takeaways.
Example: The app integrates with an AI-based text summarization API to generate short summaries of books.
Why: Helps users recall book content easily.

Fetch Book Recommendations: As a user, I want to receive book recommendations based on my reading history so that I can discover new books.
Example: The app integrates with an external book recommendation API to suggest personalized book lists.
Why: Enhances reading discovery and engagement.

