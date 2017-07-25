A. Displays all of the projects
    1. The HTTP Verb and URL: GET '/projects'
    2. The rails controller action: projects#index
    3. The corresponding CRUD action: READ
    4. The corresponding ActiveRecord method: all
    5. The corresponding SQL: SELECT * FROM projects
B. Displays information about one project
    1. The HTTP Verb and URL: GET '/projects/:id'
    2. The rails controller action: projects#show
    3. The corresponding CRUD action: READ
    4. The corresponding ActiveRecord method: find
    5. The corresponding SQL: SELECT * FROM projects WHERE id=?
C. Displays a form to create a new project
    1. The HTTP Verb and URL: GET '/projects/new'
    2. The rails controller action: projects#new
    3. The corresponding CRUD action: 
    4. The corresponding ActiveRecord method: 
    5. The corresponding SQL: 
D. Creates a new project based on given parameters
    1. The HTTP Verb and URL: POST '/projects'
    2. The rails controller action: projects#create
    3. The corresponding CRUD action: CREATE
    4. The corresponding ActiveRecord method: create
    5. The corresponding SQL: INSERT INTO projects (<fields>) VALUES (?, ?, ... ?)
E. Displays a form to update an existing project
    1. The HTTP Verb and URL: GET '/projects/:id/edit'
    2. The rails controller action: projects#edit
    3. The corresponding CRUD action: READ (to get the current info)
    4. The corresponding ActiveRecord method: all
    5. The corresponding SQL: SELECT * FROM projects
F. Updates an existing project with given parameters
    1. The HTTP Verb and URL: PATCH '/projects/:id'
    2. The rails controller action: projects#update
    3. The corresponding CRUD action: UPDATE
    4. The corresponding ActiveRecord method: update
    5. The corresponding SQL: UPDATE projects SET [<field>=?]+ WHERE id=?
G. Deletes an existing project
    1. The HTTP Verb and URL: DELETE '/projects/:id'
    2. The rails controller action: projects#delete
    3. The corresponding CRUD action: DELETE
    4. The corresponding ActiveRecord method: destroy
    5. The corresponding SQL: DELETE FROM projects WHERE id=?

