# Full Stack Airbnb Clone with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth 2023

This is a repository for a Full Stack Airbnb Clone with Next.js 13 App Router: React, Tailwind, Prisma, MongoDB, NextAuth.
## [live at Versel (click here) ](https://house-rent-livid.vercel.app/)

<img width="1728" alt="Screenshot 2023-08-22 at 2 41 20 AM" src="https://github.com/anshyadav-cmd/Airbnb-clone/assets/57345756/5cbfe4a4-9ff3-4c6c-a56b-f1decd2249cf">

<img width="1728" alt="Screenshot 2023-08-22 at 2 41 20 AM" src="https://github.com/anshyadav-cmd/Airbnb-clone/assets/57345756/4d32b4cb-2921-4f27-85b0-9fe517e93f09">

https://github.com/anshyadav-cmd/Airbnb-clone/assets/57345756/38f108a3-3a85-4244-b248-8612b4014c70


Features:

- Tailwind design
- Tailwind animations and effects
- Full responsiveness
- Credential authentication
- Google authentication
- Github authentication
- Image upload using Cloudinary CDN
- Client form validation and handling using react-hook-form
- Server error handling using react-toast
- Calendars with react-date-range
- Page loading state
- Page empty state
- Booking / Reservation system
- Guest reservation cancellation
- Owner reservation cancellation
- Creation and deletion of properties
- Pricing calculation
- Advanced search algorithm by category, date range, map location, number of guests, rooms and bathrooms
    - For example we will filter out properties that have a reservation in your desired date range to travel
- Favorites system
- Shareable URL filters
    - Lets say you select a category, location and date range, you will be able to share URL with a logged out friend in another browser and they will see the same results
- How to write POST and DELETE routes in route handlers (app/api)
- How to fetch data in server react components by directly accessing database (WITHOUT API! like Magic!)
- How to handle files like error.tsx and loading.tsx which are new Next 13 templating files to unify loading and error handling
- How to handle relations between Server and Child components!

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next13-airbnb-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GITHUB_ID=
GITHUB_SECRET=
NEXTAUTH_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |


<br/>

## Technologies and Packages used

| Technology         | Description                                                                                                                                                                                                                                |
| ------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Next.js            | Framework of React                                                                                                                                                                                                                       |
| MongoDb            | DB                                                                                                                                                                                                                                       |
| Prisma             | Prisma is a modern database toolkit<br>with ORM (Object Relational Mapping)<br>capabilities(Similar to mongoose)                                                                                                                         |
| TailwindCSS        | UI Design                                                                                                                                                                                                                                |
| NextAuth           | NextAuth.js is an open-source authentication <br>library for Next.js, a popular React framework, <br>that simplifies the process of adding various <br>authentication strategies like OAuth, JWT, <br>and more to your web applications. |
| Cloudinary CDN     | image uploads                                                                                                                                                                                                                            |
| next-cloudinary    | for nextjs                                                                                                                                                                                                                               |
| React-hook-form    | client form validation                                                                                                                                                                                                                   |
| React-toast        | server err handling                                                                                                                                                                                                                      |
| react date range   | Calendars                                                                                                                                                                                                                                |
| Vercel             | deploying                                                                                                                                                                                                                                |
| Zustang            | State Management Lib for React (like Redux)                                                                                                                                                                                              |
| Axios              | JS (lib) used to make HTTP requests from a web browser or a Node.js environmen                                                                                                                                                           |
| React-hook-form    | form validation                                                                                                                                                                                                                          |
| React-hot-toast    | React notifications.                                                                                                                                                                                                                     |
| Auth.js (NextAuth) | Authentication for the Web                                                                                                                                                                                                               |
| brcypt             | password encryption                                                                                                                                                                                                                      |
| Query String       | Parse and stringify URL [query strings](https://en.wikipedia.org/wiki/Query_string)                                                                                                                                                      |
| world-countries    |  repository contains a list of world countries                                                                                                                                                                                           |
| react-select       | The Select control for [React](https://reactjs.com/).                                                                                                                                                                                    |
| Leaflet            | library for **mobile-friendly interactive maps**                                                                                                                                                                                         |
| date fns           | It's like [Lodash](https://lodash.com/) for dates                                                                                                                                                                                        |
| react date range   |                                                                                                                                                                                                                                          |
| react spinners     | for loading screen                                                                                                                                                                                                                       |

