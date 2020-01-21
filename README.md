# Casting Agency

## Backend API and Postgres database are hosted in Heroku

### Heroku API URL: https://castingya.herokuapp.com

## The frontend application that connects to Heroku is in development mode and runs loacally

### Two roles with specific permissions are used: Producer and Director

Sample accounts for each role have been created and provided or can be provided in private message

### Frontend application depencies: Node and NPM: from https://nodejs.com/en/download

within the frontend directory in your terminal, run:

```bash
npm install
```
and then:

```bash
npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in the browser

## Casting Agency Specifications

* The Casting Agency is responsible for creating movies and managing and assigning actors to those movies.

* Models:

  * Movies with attributes title and release date
  * Actors with attributes name, age and gender
* Endpoints:
  * GET /actors and /movies
  * DELETE /actors/ and /movies/
  * POST /actors and /movies and
  * PATCH /actors/ and /movies/
* Roles:
  * Everyone
    * Can view actors and movies
  * Casting Director
    * All permissions a everyone has and…
    * Add or delete an actor from the database
    * Modify actors or movies
  * Executive Producer
    * All permissions a Casting Director has and…
    * Add or delete a movie from the database
