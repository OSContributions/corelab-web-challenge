Hello!

As you may notice by the commits, I've been working on
the project for the last three days, and I couldn't 
finish it due to a problem with the energy supply 
where I live.

That's my complete code repository:
https://github.com/williamguilhermesouza/notes-app

The frontend and backend are separated there.

That said, I'll go to the code, beginning with the 
backend:

#### Backend

The backend is built in NestJS, a good and complete framework.
I used it because it has a lot of features, and is really good
when you want to scale the app in the future.

With NestJS I used typescript, and the types of the language
gives extra security against type and input mismatching errors.

I began creating the module of the note app, and then gone downwards
to the database, following a logic like, module - controller - service.

Also in the beginning I created the interface that defined a note, and in the future I created the entity, used by the ORM TypeORM.

After all the basic logic was done, I worked on the logic out of the basic CRUD model, the filters and the order. It wasn't really dificult, because of the ORM features.

And finally I just included CORS support for the communication with the frontend.

#### Frontend

Instead of only using React, I used NextJS framework. That's because 
create-react-app is deprecated, and the recommendation for creating
an app in the React Documentation page is using the create-next-app.

NextJS has some good futures, like using typescript out-of-the-box,
something I had to configure in pure React.

In the Frontend I worked first on structuring the elements and components
then I created a minimum style for then. After that I began to work out
the linking between the components and for the last part I did the logic.

I myself used to-do lists to organize myself with the app goals, so I've
always worked with goals.

