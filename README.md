# Sweet Project Title

This is the part where I tell you about the project. The "pitch", if you will. I'm giving you a high level overview of what the project does, and why I decided to build it. This doesn't have to be extensive, just a quick overview.

This is the repo for, say, the frontend of the app. It's hosted [here](http://some.hosting.service/myapp) and the backend repo is [here](http://github.com/itsame/myapp-backend).

## User Stories

* As a user, I want to be able to create an account, so I can log in and use the app.
* As a user, I want to be able to see my user info, so etc etc etc
* As an editor, I want to be able to do an admin thing, so I can etc etc

(Have one story for each feature you plan to include—even small features are great to list here, so feel free to get granular with it. You'll probably be making a new branch for each of these, right?)

## Models and Relationships

This is a good place for a sweet diagram:

![My Data Relationships](https://support.bizzdesign.com/download/attachments/39814141/worddav928fdea0a6b423e337e8814628445af4.png)

### User

A `User` has many `Pickles`, and so on and so forth

* id
* username
* password_digest
* firstname
* lastname
* birthday
* favorite color

### Pickle

A `Pickle` belongs to a `User`, and so on 

* id
* variety
* weight
* price
* description

## API

Here's where you want to describe each API endpoint you're building/using. You can put this in your front end repo, your back end repo, or both.

### GET /api/users

Returns a list of all users. Response JSON looks like this:

```json
{ 
  id: 111,
  username: "johndoe",
  firstname: "John",
  lastname: "Doe",
  etc: "etc"
}
```

### POST /api/users

Creates a new user. Say more about that here. Send this data:

```json
{ this is what it takes as data }
```

And this is what it returns:

```json
{ this is what you get back }
```

## Wireframe / Mockup

Put your sweet wireframes and mockup images here. Probably only goes in the front end repo.

![Wireframe](https://i2.wp.com/d1dlalugb0z2hd.cloudfront.net/handbooks/agile-handbook/wireframe/01-youtube-wireframe-example.png?resize=800%2C528&ssl=1)

![Another Wireframe](https://dpbnri2zg3lc2.cloudfront.net/en/wp-content/uploads/old-blog-uploads/versions/samuel-student-wireframe---x----972-715x---.png)

## Contact info and other stuff

Put anything else you want here!