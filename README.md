# Study Timer

## Specification Deliverable

### Elevator Pitch
  Need a friend to stay on track with anything? Can't have your friends with you all the time? Then StudyTimer is that friend! This timer is built top to bottom to help you stay on track with your goals and that future. Small steps lead to great things, and we help you with that. We have the Pomordoro Timer to help with studying, and the kitchen timer to help with cooking or to help you move on to your next activity. We even keep track of you and your friends stats so you can track your progress over time. Our Studytimer is perfectly set up to give you the nudge you need to stay productive. 
  
### Design

### Key Features
* Secure login over HTTPS
* Display of timers/buttons for settings
* Customizable study timers (Pomodoro study timer, classic Kitchen timer, break timers, etc.)
* Customizable backdrop for timer
* Results from study sessions are continuously stored (i.e. how long studied, which days)
* Totals from all users' study sessions are displayed in realtime

### Technologies
The following technologies will be used + descriptions:
* HTML - I will use correct HTML structure for this application. Two HTML pages will be used. One for login, and one for the timers/studying. There also may be several popups within the timers/studying page for settings. Potentially hyperlinks to music for studying.
* CSS - Will be used to style my webpage to look on different screen girths, additionally using good whitespace, color choice, and contrast (like the principles in CS 202 C.R.A.P.)
* JavaScript - Will be used to creat the login page, setting display, applying settings/user prefrences, display users study time statistics, backend endpoint calls.
* Service - there will be backend service with endpoints for:
  * login
  * retrieving setting prefrences
  * retrieving study status
  * DB/Login - Store users, setting prefrences, and stats in database. Register and login users. Credentials securely stored in database. Can't keep track of time studied unless authenticated.
* WebSocket - After each user's study session, their stats are broadcast to all other users.
* React - Application ported to use the React web framework.


### HTML Deliverable

### CSS Deliverable

### JavaScript Deliverable

### Service Deliverable

### DB/Login Deliverable

### WebSocket Deliverable

### React Deliverable

