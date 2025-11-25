# Social Book

A fully functional social media application built with Django.

## Features

*   **User Authentication**: Secure Sign Up, Sign In, and Logout.
*   **Profile Management**: Customize your profile with a bio, location, and profile picture.
*   **Social Networking**: Follow and unfollow other users. Get suggestions for who to follow.
*   **Content Creation**: Upload images with captions.
*   **Feed**: Personalized news feed showing posts from people you follow.
*   **Interactions**:
    *   **Likes**: Like posts to show appreciation.
    *   **Comments**: Engage with posts by adding comments.
*   **Search**: Easily find other users by username.

## Getting Started

### Prerequisites

*   Python 3.x
*   pip

### Installation

1.  Clone the repository:
    ```bash
    git clone <repository-url>
    cd Social-django
    ```

2.  Install dependencies:
    ```bash
    pip install django pillow
    ```

3.  Apply database migrations:
    ```bash
    python manage.py migrate
    ```

4.  Run the development server:
    ```bash
    python manage.py runserver
    ```

5.  Open your browser and navigate to `http://127.0.0.1:8000`.

## Usage

1.  **Sign Up** for a new account.
2.  **Edit your Settings** to add a profile picture and bio.
3.  **Search** for users or check the "Users You Can Follow" section.
4.  **Upload** a photo to share with your followers.

