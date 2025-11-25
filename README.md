Fetch and Display Data from a Public API Using Fetch API
🎯 Objective

Use the JavaScript Fetch API to retrieve user data from a public API and display it on a webpage in a clean, readable format.

🛠️ Tools Required

VS Code

Chrome Browser

Internet Connection (for API fetching)

📌 Features

✔ Fetch user data from a public API
✔ Dynamically display user details (name, email, address)
✔ Handle errors using try...catch
✔ Reload button to refetch data
✔ Styled layout for readability

🌐 Public API Used

We use the free placeholder API:

https://jsonplaceholder.typicode.com/users

🧩 Steps to Complete the Task
1. Create the HTML Structure

Add a container to display fetched users

Add a reload button

Link CSS & JS files

2. Write JavaScript Using Fetch API

Use fetch() to request user data

Convert response to JSON

Loop through the array and generate DOM elements

Display:

Name

Email

Address (street, city, zipcode)

Add error handling with catch

Add reload button functionality

3. Style With CSS

Add card-like UI

Improve spacing, fonts & layout

Make responsive if needed

▶️ How to Run

Open the project folder in VS Code

Run index.html using "Open with Live Server" (recommended)

View user data displayed on the webpage

Disable internet to test error handling

Click Reload to fetch data again

🧪 Expected Output

A list of users displayed in card format

Each card shows:

Name

Email

Address (street + city + zipcode)

Error message shows when offline

Reload button fetches data again
