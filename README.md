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

Check out the app for a full user experience:  https://incented-protocol-git-prioritizevalida-b9e591-wookie3s-projects.vercel.app

## Development Notes

Due to the scope of the project, not all of the original features were achieved.  The following are examples of some of the features that were realized.  

- View & submit proposal
- A user's ability to view & submit proposals, prioritize, contribute, and validate
- Creating & viewing communities along with funding them
- Funding a user's individual account
- User login & registration

The incented team intends to "dog-food" this web2 version into a fully useable web3.0 version.  

# Application Architecture Design

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


## User Stories

### ***Users***

*EPIC:*  A user (Rabbit) wants to contribute to a community and be compensated (Rabbit Hole).

- As a user I want to define the title, description, time estimation, validation period and expiration date for a contribution so that the proposed task is completed.
- As a user I want to be able to view all the tasks that are available in my community so that I can contribute and be rewarded.
- As a user, I want to be able to propose tasks, so I can suggest projects that align with our app’s goal.
- As a user, I want to submit a task so that I along with others can work on it.
- As a user, I want to claim a task so that I can contribute to it .
- As a user, I want to submit a contribution so that I can provide a solution to a proposed task
- As a user, I want to review a contribution so that I can provide a stake for or against the contribution. 
- As a user, I want to be rewarded for a task proposal, ensuring that contributors are fairly compensated for their contributions.
- As a user I want to be able to see my wallet balance so that I can make contributions to my community.

### ***Community Administrator (Dams & Sires)***

*EPIC:* A community administrator wants to manage a community and ensure there is no mal intent.

- As an admin, I want to manage communities so that I can provision and configure the protocol, adjust requirements (timeframes/rewards), set/adjust prioritizer reward.
- As an admin, I want to maintain the platform, ensuring that the App remains secure and accessible to the community.
- As an admin, I want to have veto power over my community for tasks with malicious intent. 
- As an admin, I want to request a specific amount of carrots from the incented team so that I can sufficiently fund the rewards for a proposal in the community.  

### ***Super Administrator (Incented Team)***

*EPIC:* A super admin wants to manage individual communities (Rabbit Holes) and distribute funds to them (carrot pot).

- As a super admin, I want to manage individual communities & members so that I can control who has access and assign community admins.
- As a super admin, I want to be able to view a list of all task proposals and their statuses, allowing others to see projects or contributions.
- As a super admin, I want to distribute carrots to community admins so that I can enable those admins to sufficiently fund their proposals. 
- As a super admin, I want to review and respond to user feedback, and inquiries to maintain a positive user experience

