This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

The app allows to browse events, select a single event and filter for events. 

There is an events page. The user can explore individual events and filter them by selecting the year and month filters.

The app uses dummy back end on Firebase so the dummy data can be fetched from there.  

There is a newsletter registration flow – a component that allows a visitor to enter an email address and then stores that email address with help of api routes

There is a Comments feature – users can submit a form to add comments on an event – that entered comment data is stored on the backend with help of api routes. 

When we load the single event we are able to load the comments when the user wants to view the comments section.


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

