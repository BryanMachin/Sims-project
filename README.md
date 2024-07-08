# Sims-project

The Sims project proposes to provide the user with a friendly environment in which they can model the main characteristics of the game The Sims 4. For example, creation of sims, household units, jobs, among others. It also allows the link between all entities, for example: Sim A lives in house B and his profession is C. The main objective is to conceive the relationship with the database through the basic actions of creating, reading, updating and deleting from the player's environment.

## Keywords:
- Model-View-Controller
- ASP.NET
- Entity Framework
- Web Application
- C#
- HTML
- CSS
- SQL

## Requirements:
-  Microsoft.EntityFrameworkCore.SqlServer
-  Microsoft.EntityFrameworkCore.Tools
  
This is the main screen of the application, through which the user can navigate to the Index view of the corresponding entities.

![Main view](/Reports/main%20view.png)

The following image shows the Sim entity, which contains a list of all the sims that belong to the database. It is observed that the names of the sims are written with a different color than the rest of the fields shown in the table, and these are a link that redirects the user's navigation to the Profile view of each sim.

![Sims list view](/Reports/sims%20list%20view.png)

In a Sim's Profile view, the relationships between it and other entities are observed, where we can choose another job, go to work, change the house where they live, among other options.

![Sim profile](/Reports/sim%20profile.png)

We can also improve the Sim's skills by doing activities.

![Activities](/Reports/activities.png)

![Skills](/Reports/skills.png)

For more details about the project:

- [Academic Report (In Spanish)](/Reports/informe%20académico.pdf)

- [Technical Report (In Spanish)](/Reports/informe%20técnico.pdf)

- [User Manual (In Spanish)](/Reports/manual%20de%20usuario.pdf)