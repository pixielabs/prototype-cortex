# README

This README would normally document whatever steps are necessary to get the
application up and running.

# Ruby Version

- rbenv version 3.3.5
- ruby version 3.3.5

# Backend Setup 

- rails db:create
- rails db:migrate
- rails db:seed

# Frontend Setup

- npm init -y
- npm install react react-dom --no-optional --foreground-scripts --verbose
- bundle install
- bundle exec vite install
* (you should see a positive confirmation message in the terminal that Vite has been installed successfully after following the steps above)
- exec "SHELL"

# Running the application locally

- In a separate terminal window in the project root directory run the following command: bin/rails server
- This will launch the Rails backend for the application

- In another separate terminal window in the project root directory run the following command: bin/vite dev
- This will run the Vite bundler for the frontend and make the frontend of your application live

- Launch the application in the browser by using the appropriate local host URL e.g. http://127.0.0.1:3000/

# How does the application actually work 

- The Cortex AI prototype has been developed to simulate the happy path for the application by demonstrating the application's ability to resolve a query for the User and provide an adequate response.
- At present, Cortex AI is able to resolve the following queries:
  1) What are the constraints of scheme eligibility?
  2) Can a borrower contract multiple loans under the BBLS (BBLS)?
  3) Can I transfer a loan to another borrower within the Recovery Loan Scheme (RLS)?

- These queries can be typed in any order and Cortex AI will resolve them however the application at present is unable to resolve queries outside of this collection and will raise an error in this event.

- Below is a short product demonstration capturing Cortex AI in action, presenting how to use the application correctly.

- https://www.loom.com/share/7f9be89603e245f9beadee25e9abb608?sid=ab09e8c8-b55e-4335-9659-6b3f30bdd5ea



