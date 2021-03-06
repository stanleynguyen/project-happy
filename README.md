# Project Happy

This project is aimed to provide a helping hand to special-need teachers at VSA
by means of a web application.

### Rationale

One way to calm autistic children is letting them watch Youtube videos.
However, this poses another problem of the child get carried away and the teacher
not being able to stop them from watching to move on to other activities.

### Proposed solution

This web application will be a Youtube video streamer with an integrated timer
that allows teachers to set maximum time for the children to watch.
The video will be followed by visual instruction for the child to move on to other activities.

### Tech stack

- HTML5/CSS3/Javascript
- ReactBootstrap
- ReactJS/Redux
- Youtube API

### Getting started

```
git clone git@github.com:stanleynguyen/project-happy.git
cd project-happy/
npm install
npm run dev
```
and start coding!

to push changes:
```
npm run build && git push
```

### Checklist
- [x] Youtube Streaming and play duration timer
- [x] options for directing after-video activities
- [x] options for before-video activities
- [x] switch to react for ease of maintenance while still user-experimenting
- [x] Redux for a better architecture
- [x] transform into progressive web app to eliminate address bar (a possible distraction for the kid)
- [ ] videos bookmarking feature
