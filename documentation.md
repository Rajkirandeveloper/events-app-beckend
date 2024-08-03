API Routes
User Authentication
Register: POST /register

Description: Register a new user.
Login: POST /login

Description: Log in an existing user and create a session.
Event Management
Create Event: POST /events

Description: Create a new event.
Retrieve Events: GET /events

Description: Retrieve all events for the logged-in user.
Update Event: PUT /events/:id

Description: Update an event by ID.
Delete Event: DELETE /events/:id

Description: Delete an event by ID.
Session Management
Retrieve Sessions: GET /sessions
Description: Retrieve all user sessions.
Weather Information
Fetch Weather: GET /weather/:location
Description: Fetch weather information for a given location.