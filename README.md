# Rails Take Home Test - Add Sharing

This repository contains a Rails application designed to showcase your understanding of core Rails concepts and testing practices. 

## Table of Contents

1. [Overview](#overview)
2. [The Assignment](#the-assignment)
3. [Getting Started](#getting-started)
5. [Delivery](#delivery)
5. [Hints](#hints)

## Overview

This is a rails app for managing generic `Projects`.\
Users can create `projects` and add `reports`/`documents` to them.\
Currently, **only the creator of a project is able to view the project and it's associated resources (reports/documents).**

**We want the ability for users to share their created projects/reports/documents with other users.**\
**We also want the ability to assign certain permissions when sharing - allow different levels of access to each individual resource.**

* **Tech Stack:**
    * Ruby on Rails 
    * SQLite (database)
    * RSpec (testing framework)
    * React
        - [tailwindcss](https://tailwindcss.com/) - css
        - [shadcn](https://ui.shadcn.com/) - ui components
     
* **Current Application**
  * Check out this loom demo of the current state of the application\
  https://www.loom.com/embed/a5b1adec883d477481f6f6640f904ad1?sid=95aa56b7-79a4-4ead-adda-b1300fde0153

## The Assignment

Update this rails application with the necessary changes to allow creators of `Project`s, `Report`s and `Document`s the ability to share their creations with other users.

Users should also have the **ability to assign a permission level when sharing a resource.**\
The permissions levels should resemble the following:
- **Full Access**
    - User can edit the resource, manage sharing and view/edit/create/manage sharing on any subresources.
- **Edit**
    - User can view and edit the resource and any subresources only, with no ability to create or manage sharing.
- **View**
    - User has view-only access to the resource and its subresources.

**Add the Model(s) and API(s) necessary to allow users to do the above and unit/integration test coverage around these changes.**

### Extra credit

- Include Technical Documentation about your changes.
- Update the front-end with UX for sharing a project/report/document with other users.
- Refactor! No application is perfect and this one is no exception. Refactors welcome, leave comments so we know why.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Site-Marker/sharing-refactor.git
   cd sharing-refactor
   ```
2. **Checkout a new branch:**
   ```bash
   git checkout -b [your first name]/take-home-assessment
   ```

3. **Setup enviroment:**
   ```bash
   bin/setup
   bin/dev
   ```

4. **Code:**
    Local application should be live at http://localhost:5000 - time to code!

5. **Run tests:**
   ```bash
   rspec
   ```

## Delivery

When your changes are complete push your new branch and open Pull Request to `main` branch.\
If you decided to include Technical Documentation of your changes please include a link in the PR description.\
Please spend no-more **2 hours on the assignment**.

### Happing coding! Looking forward to see what you came up with :)

## Hints

We've provided some default users in the db seeds.
If you want a user that has resources ready to share\
You can login with

email: `robertpaulson@example.com`\
password: `testing123`

**AI/LLMs:**

Did you use AI tools to help you with this assignment? 

*GREAT!!!*

It's a brave new world of software development and leveraging these tools are imperative.\
Let us know which tools you used and how they helped you find a solution.\
*P.S. This project is setup to support the use of https://v0.dev/ ;)*
