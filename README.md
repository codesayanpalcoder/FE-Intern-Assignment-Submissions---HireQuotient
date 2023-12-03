## PROJECT REPORT 
# Table of Contents
1.Introduction<br>
2.Requirements<br>
3.Implementation<br>
4.API Integration<br>
5.Conclusion
## <a> Introduction</a>
<h2> The Admin User Interface (UI) is a web-based application designed to assist administrators in managing users. The UI fetches user data from an API and provides features such as viewing, editing, deleting, and filtering users' information. This documentation outlines the requirements and implementation details for building the Admin UI in React.Js</h2> <br>
## <a> Responsibilities</a>
<strong>Column Titles Standout:</strong> Columns in the user table should have distinguishable titles from the user entries.
<strong>Search Functionality:</strong> Implement a search bar to filter users based on any property.
<strong>Edit/Delete in Place:</strong> Enable editing or deleting rows in memory without persistence.
<strong>Pagination:</strong> Implement pagination for 10 users per page with navigation buttons.
<strong>Dynamic Pagination:</strong> Pagination should update based on search/filtering results.
<strong>Row Selection:</strong> Enable selecting one or more rows with a grayish highlight.
<strong>Delete Selected Rows:</strong> Ability to delete multiple selected rows.
<strong>Select/Deselect All Rows:</strong>strong> Checkbox to select/deselect all displayed rows on the current page.

## <a> Implementation </a>
The Admin UI will be developed using a combination of HTML, CSS, and JavaScript. Libraries like React.js and Material UI template  is  utilized for efficient component management and state handling. The UI components will include:

#User table with distinguishable column titles using Material UI
#Search bar for filtering users.
#Pagination controls for navigating through user pages.
#Row selection functionality with checkboxes.
#Edit and Delete actions for individual rows.
#'Delete Selected' button for batch deletion.




**Note :**
The users are sorted by `id` field. There is no alphabetical sorting.

**Request Type :**
GET

**Endpoint :**
https://geektrust.s3-ap-southeast-1.amazonaws.com/adminui-problem/members.json

**Sample Response :**


    [
    {
      "id": "1",
      "name": "Aaron Miles",
      "email": "aaron@mailinator.com",
      "role": "member"
    },
    {
      "id": "2",
      "name": "Aishwarya Naik",
      "email": "aishwarya@mailinator.com",
      "role": "member"
    },
    {
      "id": "3",
      "name": "Arvind Kumar",
      "email": "arvind@mailinator.com",
      "role": "admin"
    }

    
    ]
## <a name="conclusion"></a>
The Admin UI project aims to create a functional interface for administrators to manage users effectively. By meeting the specified requirements, the UI will provide a seamless experience for viewing, editing, and deleting users' information sourced from the provided API.
