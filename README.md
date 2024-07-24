# ChatSphere

Chatsphere is a Django-based application designed for collaborative learning. It allows users to create and join discussion rooms, participate in conversations, and manage topics related to their interests.

Features
1. User Authentication

    Registration: Users can sign up with a username and password. After registering, they are automatically logged in.
    Login: Existing users can log in using their credentials.
    Logout: Users can log out to end their session.

2. Room Management

    Create Room: Authenticated users can create rooms with a name, description, and topic.
    Update Room: Hosts can modify room details.
    Delete Room: Hosts can delete their rooms and all associated messages.

3. Message Management

    Send Messages: Users can post messages in rooms they are part of.
    Delete Messages: Users can delete their own messages.

4. Topic Filtering

    Browse Topics: Users can view and select topics.
    Filter Rooms: Users can filter rooms by selecting a topic.

5. Recent Activity

    View Recent Messages: Displays recent messages from all rooms, including message content, sender, and time since posted.

    Requirements

    Python 3.8+
    Django 5.0.6
