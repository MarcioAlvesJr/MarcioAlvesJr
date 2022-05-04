



# The Project

<p>This is a fullstack application meant to keep track of how much time was spent on a specific goal, skill and etc. The app does it by creating focus sessions.</p>
<p>The user can create a session an then associate it with the desired tag. It’s possible to see how much time has been put to each tag and also take a look at all sessions in a calendar.</p>
<p>The project was created during my free time using the MERN stack(MongoDB, Express.js, React.js and Node.js) in the matter of practicing my skills and also displaying them in my portfolio. </p>

- [Repository Links](#repository-links)
- [Frontend](#frontend)
  - [Tags](#tags)
  - [Timer](#timer)
  - [Calendar](#calendar)
- [Backend](#backend)

# Repository Links
 - [Frontend Code](https://github.com/MarcioAlvior/THE-GOAL-HELPER)
 - [Backend Code](https://github.com/MarcioAlvior/THE-GOAL-HELPER_backend)

# Frontend
  <p>All HTTP requests to the backend and async state-management are done through Axios and React Query. Once one change happens the application is updated accordingly with the help of React Context.</p>

## Tags

<p>Tags can be created, edited and deleted. Tags list, tag form and schema validation were created using Material UI, Formik and YUP. </p>
<img alt="Demonstration 1" height="500" src="https://github.com/MarcioAlvior/MarcioAlvior/blob/main/Projects/TheGoalHelper/Demonstration_1.gif" />

## Timer
<p>Once the focus session starts the timer is running.  While the timer is running it’s possible to associate the session with a tag. It’s also possible to interact to the tags page, make changes. Timer screen will react consequently.</p>
<p>When the timer is done you can save the focus session and then restart the timer for another one.</p>
<img alt="Demonstration 1" height="500" src="https://github.com/MarcioAlvior/MarcioAlvior/blob/main/Projects/TheGoalHelper/Demonstration_2.gif" />

## Calendar
<p>Focus Sessions can be seen via FullCalendar. By clicking on one session it’s possible to see more details and change the associated tag.</p>
<img alt="Demonstration 1" height="500" src="https://github.com/MarcioAlvior/MarcioAlvior/blob/main/Projects/TheGoalHelper/Demonstration_3.gif" />

# Backend
- Server routing and HTTP requests happen via Express.js.
- The server uses Mongoose to create models schemas and access a MongoDB database.




