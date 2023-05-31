# bord__dokumentation
Dokumentation till projekt Bord och dess teman

# Welcome new 4th term studends, This is the past years 4th graders speaking!
## What is this? (And why should you read it?)
this will be a short guide for you to look at, where we explain the problems we encountered while working on the project. What we in hindsight could have done differently. And how you can succeed where we did not...

### Choose the right backend
- When we started this project we were trying to set up a database that could be pushed up to GitHub. Don't do this, Seriously don't! Just keep it local, and keep it simple.
- I can't really remember how we chose to set up the database, But whatever we did was stupid. If i remember right the backend was mostly working using JS and this is just plain and simple wrong. Use C# for all that logic, You will probably need to learn it anyways so why not use it for this project? Look [HERE](https://learn.microsoft.com/sv-se/aspnet/core/tutorials/first-web-api?WT.mc_id=dotnet-35129-website&view=aspnetcore-7.0&tabs=visual-studio) to find documentation for creating a webAPI with ASP.Net Core. **Keep in mind that this might not be exactly what you want either, But it sure is a step in the right direction**
- I would also recommend that you run the backend as a whole on the client computer instead of setting up a login and administration page, This means that the client won't need internet connection to run the system and therefore can use it anywhere in the world. *Eg. at an exhibition* This comes with it's own problem... Administration 😨 *read more about that further down in this documentation*

### Now for the frontend, This is where the fun begins ☕ 
- First of all. The NFC/RFID logic has to happen here. Probably using JS or something similar. Depending on what Ronnie wants this can cause problems. Think of him as the customer that does not know what he wants, And wants everything at the same time. He will probably want you to use an tablet of some sort. This means that you will be limited with how the logic works, Mostly for the backend... But the frontend will be very simple if this is the case. all you need to do for this is steal some code. Look [HERE](https://github.com/tcstenungsund/bord__frontend/blob/main/js/nfc.js) for inspiration. The repo as a whole is a good place to start looking when in need of help. It is by all means not finished but will probably give you something to work with.
- Create a PWA, It won't hurt you even if it is really tedious to write a good SW.
- Do your own thing. Find new solutions to display the data.

### The project as a whole
- This project is one of the most rewarding projects you can work on, If you do it right. Get together and talk to each other. Find out what the team wants, Who is good at what, and give everyone a clear role. Everyone needs to know what they should be working on.
- **I can not stress this enough, Choose a leader** This will benefit you a lot. The leader should not be someone who is programming the whole site. This is someone who takes responsibility for the project, Who makes the decisions for the project and is fine with sitting down and discussing about the project. This person also needs to take the time to guide everyone else towards success.

### Summary
1. Get a clear picture of what you are doing, and what everyone else is doing.
2. Start setting up the project, Look through past projects (links down below)
3. Plannig, Planning and Planning. If you don't have a plan, Nothing good will come.
4. Work
5. Don't have fun 😄

**Repositorys that might be useful in some way** 
- This repo ofc
- [The frontend repo for this project](https://github.com/tcstenungsund/bord__frontend)
- [The backend repo for this project](https://github.com/tcstenungsund/bord__backend)
- [Klovaaxel's repo for bord v1](https://github.com/klovaaxel/info-table)
- [Pontalainen's repo for the laravel version of bord](https://github.com/pontalainen/bord_laravel)

Good luck suckers!!!
