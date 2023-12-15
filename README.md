# Incented-Protocol (Web2-App)

This is a NextJS-based app built in partnership with York University, which serves as a graduation project.  

## Purpose

Incented Protocol is a web2 application that provides a transparent user-friendly platform for communities & DAOs to coordinate and incentivize the completion of tasks.  Community members have the ability to contribute to a task while being rewarded for their efforts.  

The user-base consists of community users, community administrators, and super administrators.  Users will be able to propose, prioritize, contribute, review a proposed task while community administrators will manage their community and associated funds used for incentivizing tasks.  On the other hand, super administrators will manage all communities, members, and distribution of funds to each community.  

## Getting Started

First, run the development server:

```bash
npm run dev

```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

If pulling from github for the first time, you may need to re-install its dependencies.  Run the following:  `npm install`

This app uses Tailwind CSS. If encountering issues, run the following: `npm install -D tailwindcss postcss autoprefixer`

## Deployment

Incented protocol is deployed and hosted using [Vercel](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme).  

**Check out the Demo:**  https://incented-protocol-git-prioritizevalida-b9e591-wookie3s-projects.vercel.app

## Development Notes

Due to the scope of the project, not all of the original features were achieved.  The following are examples of some of the features that were realized.  

- View & submit proposal
- A user's ability to view & submit proposals, prioritize, contribute, and validate
- Creating & viewing communities along with funding them
- Funding a user's individual account
- User login & registration

The incented team intends to eventually "dog-food" this web2 version into a fully functioning web3.0 version.  

## Key Terms

| Term  | Description |
| ------------- | ------------- |
| Rabbits🐰 | Stores user information  |
| Rabbit-Hole🐰🕳️ | A specific community in the Incented protocol |
| Dams and Sires | Administrators of the Rabbit-Hole |
| Carrots🥕 | The protocols form of reward that is also used to interact on the protocol (e.g.stake on proposals, etc.).  For this version, these are simply “points” of that are tracked in a database |
| Wallet | A digital representation of the users funds (store for carrots) |
| Carrot-Pot | Treasury of a community where rewards come from |
| Staking  | A core interaction performed with Carrots |
| Protocol Fee | A fee that is deducted from the users Wallet when they interact with the protocol in the form of carrots. The protocol fee goes to the Rabbit-Holes Wallet (the Community Wallet) |
| DAO  | Decentralized Autonomous Organization |

## Technology Stack

### Front-End
- React JS with Next JS Framework
- CSS Tailwind
- Shadcn UI

### Back-End
- _Restful API:_  Next JS using App Router features
- _Database:_  PostgreSQL deployed using Supabase
- _Hosting:_  Vercel
- _Runtime Environment:_  Node JS

## Authors 

- **Incented - Main**

- York Unversity - Students
  - [@JoseArias31](https://github.com/JoseArias31)
  - [@Wookie3](https://github.com/Wookie3)
  - [@nbacc12](https://github.com/nbacc12)

