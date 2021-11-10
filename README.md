## EraGram

**Recreating Instagram's UI with React**: I'm sure people at facebook do a much better job than this 😶 

![img](ss.png)
### Notice:
This project is currently uses firebase so the [website](https://vercel.com/animeshry/eragram) won't be active as the build contains my firebase credentials. You are free to try the app locally with the instructions below.

If the website is live, you can try it with these credentials
`test123@gmail.com, test123`

## Installation and Setup Instructions

#### Example:

Clone down this repository. You will need `yarn` and `npm` installed globally on your machine.

Installation:

`yarn install`

To Start Server:

`yarn start`

To Visit App:

`localhost:3000`

## Reflection

  - This project is just a side project for gromming my react skills and does not in anyway relate to the actual Instagram Website. I'm sure the devs at Facebook do a much better job than what I tried to mimick here.
  - Project utilizes custom hooks and uses Context instead of redux, Redux is great but working alone and with no plan to work on the project after publishing tempted me to switch to useContext. After my fair share of breaking my head trying to implement this app, Context did come up out as a better option atleast for my personal projects.
  - Major problems I faced was to reduce the number of times I utilized state making the app slow, although those extra firebase calls were part of the problem too. I ended my spinning up a seperate context for firebase authentication and refactored some code to reduce the excess state usage before the final publish.
  - What tools did I use to implement this project?
      - Project is bootstrapped with `create-react-app` and utilizes tailwind (best CSS framework) for all of my styling needs. The project uses basic email authentication from firebase and stores user and post data in the firestore.

#### License:

This project is licensed under the MIT License - see the [LICENSE.md](/LICENSE) file for details.


