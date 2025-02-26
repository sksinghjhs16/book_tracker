# Book Tracker User Story
## User Stories for Registration & Login
Application Registration: As a new user, I want to register by entering my name, email, and password so that I can track my reading progress.
Application Login: As a registered user, I want to log in using my email and password so that I can access my book list and progress.
Error Feedback on Signup & Login: As a user, I want to receive error messages if I enter incorrect details during signup or login so that I can correct them.
Store User Data: As a user, I want my login details to be stored securely so that I don’t have to log in every time I open the app.

## User Stories for Home Screen
Progress Overview: As a user, I want to see an overview of my reading progress (books read, currently reading, pages completed) on the home screen so that I can track my journey.
Quick Access to Features: As a user, I want to quickly access my "Currently Reading" books, completed books, and saved summaries from the home screen so that I can navigate efficiently.

## Detail Screen User Stories
View Book Details: As a user, I want to view complete details of a book, including title, author, number of pages, and cover image (if possible), so that I can quickly access relevant information.
Track Reading Progress: As a user, I want to see my reading progress (percentage, pages read, start and finish dates) on the detail screen, so that I can monitor my progress easily.
Edit Reading Progress:  As a user, I want to update my reading progress manually (pages read or percentage completed) on the detail screen, so that I can track my progress accurately.
Add Personal Notes: As a user, I want to add and view personal notes for a book, so that I can jot down key insights or thoughts while reading.
Write & Edit Summary: As a user, I want to write and edit my book summary on the detail screen, so that I can save my understanding of the book.
Mark as Completed: As a user, I want to mark a book as completed directly from the detail screen, so that I can update my reading status quickly.
Delete Book Entry: As a user, I want to delete a book from my list via the detail screen, so that I can remove unwanted entries.
View Analytics for Book: As a user, I want to see reading time statistics and trends for a book on the detail screen, so that I can analyze my reading habits.

## Persistent Data Integration
Login State Persistence: As a user, I want my login state to persist across sessions so that I don't need to re-enter details every time.
User Preferences Persistence: As a user, I want to save my preferences such as dark mode so that the app remembers my settings.
Books Reading Status Persistence: As a user, I want to save my book entries and other details so that I can sync them in another device also or after the change of device.

## Integrate External API
External APIs enhance app functionality by allowing integration with third-party services, such as book metadata retrieval, AI-generated summaries, or progress syncing across platforms. These integrations make the app more dynamic and user-centric.

Fetch Book Details: As a user, I want to fetch book details (author, summary, genre) by entering the book's title so that I don’t have to manually input all information.
Example: The app integrates with an external book database API (e.g., Google Books API) to auto-fill book details when adding a new book.
Why: Saves time and ensures accurate book information.

Fetch Book Reviews: As a user, I want to see book reviews so that I can discover new books to read.
Example: The app integrates with an external book reviews API to get reviews to choose the right book.
Why: Enhances reading discovery and engagement.

## User Stories for Settings Menu
Access Settings: As a user, I want to access the settings menu from any screen so that I can customize my preferences.
Categorized Settings: As a user, I want settings to be organized into sections like Account, Appearance, and Notifications so that I can find options easily.

## User Stories for Settings Screen
Enable Dark Mode: As a user, I want to toggle dark mode so that I can reduce eye strain during app usage.
Notification Preferences: As a user, I want to enable or disable reading reminders so that I can manage notifications.
Update Profile: As a user, I want to update my name and password in the settings so that I can keep my account secure.

## User Stories for Notifications
Reading Reminders: As a user, I want to receive reminders to continue my current book so that I stay consistent.
Achievement Notifications: As a user, I want to receive alerts when I complete a book so that I stay motivated.
Admin Notifications: As an admin, I want to send notifications to users about app updates or new features so that they stay informed.
