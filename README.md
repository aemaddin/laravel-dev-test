# laravel Fullstack Developer Test
Test for laravel developer position 2022

## Laravel Senior Developer Test

### Using Laravel CLI:-

- [ ] Make new models (Post, Comment, Admin, User)
    - [ ] Posts table : title, content, photo, tags, timestamps
    - [ ] Comment: commentable_type, commentable_id, timestaps
    - [ ] Admin : name, email, phone,  timestamps
    - [ ] User : first_name, last_name, email, phone, profile_picture, timestamps
    - [ ] Role and Permission => use spatie package
- [ ] Make a new auth guard for admins with everything related to this guard

### Using Laravel, Inertiajs and Vuejs composition style:-

Admin Area:-

- [ ] Create a new admin route group. Only admins can access it.
- [ ] make posts resource (CRUD)
- [ ] make admin resource (CRUD)
- [ ] make user resource (CRUD)
- [ ] make comment resource (CRUD) - need permission to be approved to show it in the post’s comments

### Clients Area:-

- [ ] Create new pages for (no design is needed)
    - [ ] users profile (change personal info and profile picture, change password)
    - [ ] posts (Read only) with permissions and roles.
    - [ ] comments for each post with auditing. If approved by admin, you can see it.

### Tests:-

Create test cases for each resource you create to ensure everything works as expected.

### Finally:-

After finishing, please create a new repo on GitHub and push your project with instructions to install and run the project.

The expected time to finish the project is **1 hour**.
