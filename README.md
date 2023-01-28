# [MUST READ] Welcome to WDB's frontend technical project!

This project is designed for **you** to gauge whether you want to apply to the **bootcamp** or **industry** branch. Follow the steps below to finish and submit your project. Do not be discouraged if you get stuck. Completing all tasks for the branch you are applying to is highly preferred, but we will only assess your project based on whatever you submit to us.

If you have any questions, please reach out to us at [our email](webatberkeley@gmail.com).

## Clarifications
- None at the moment.

## Introduction

Our client is My Little Unicorn and we will be building their website. Their description is as follows.

Introducing the magical world of unicorn adoptions! We are My Little Unicorn, a unicorn adoption agency. Our platform allows you to bring a touch of whimsy and wonder into your life by adopting your very own unicorn. These mystical creatures come in all shapes and sizes and each one is as unique as a fingerprint. Whether you're looking for a playful companion or a majestic addition to your herd, we have the perfect unicorn for you. Adopting a unicorn is easy, simply browse our gallery, choose your favorite and we'll take care of the rest. So why wait? Bring a touch of magic into your life today and adopt a unicorn!

## Specifications

The skeleton code provided is in Next.js and Typescript (it's almost identical to Javascript, and you won't have trouble understanding it if you know JS). Free free to create/edit/destroy any files you want while completing this project. If you find a better solution, you should implement that instead of what is provided. If you are more comfortable in another framework, you are welcome to start a project in any other frontend framework you like. You are also welcome to use any UI component library, although Chakra UI has been used to set up most of this project. You are welcome to use NPM or Yarn when downloading dependencies. 

Use the documentation below to complete your project.

- Figma Designs: https://www.figma.com/file/hVK6z7EJGnuDks4Lz0XCaG/%5BSP-23%5D-Frontend-Technical-Project?node-id=2%3A494&t=9UqRnRczpRWANRB9-1
- Next.js: https://nextjs.org/
- Chakra UI: https://chakra-ui.com/

## Getting Started

1. Clone this GitHub repo into a local folder. 

2. Run in the project terminal

```
yarn
```

3. You can run your website by running

```
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Bootcamp Project

### Task One

Complete the Landing page UI in landing.tsx. Make sure to follow the [Figma]( https://www.figma.com/file/hVK6z7EJGnuDks4Lz0XCaG/%5BSP-23%5D-Frontend-Technical-Project?node-id=2%3A494&t=9UqRnRczpRWANRB9-1) provided. The background image is provided in the public folder.

### Task Two

Complete the NavBar navigation component in NavBar.tsx. Clicking the icon or text in the top left should take you back to the home page, clicking "About Us" should take you to the about-us page, and clicking "Gallery" should take you to the gallery page. Consult the Next.js documentation on how to do so.

### Task Three

Complete the Voting page in voting.tsx. Your task is to make a card for each previous winner (the images are given in the public folder). Each previous runner should have a default value of 0. When you click the up arrow icon or down arrow icon, the score should increment or decrement by one vote. Make sure that other values are not reset when you upvote or downvote a runner.

Feel free to create new components in the component folder and use them in this page.

## Industry Project

### Task One

Complete the Landing page UI in landing.tsx. Make sure to follow the [Figma](https://www.figma.com/file/CEX3yx0QzlfA4gmeMTlWBC/%5BFA22%5D-Frontend-Project?node-id=0%3A1) provided. The background image is provided in the public folder. The NavBar has already been completed for you (although you will be tweaking it in task two). 

### Task Two

Complete the NavBar navigation component in nav-bar.tsx. Clicking "home" should take you back to the home page, and clicking "voting" should take you to the voting page. Consult the Next.js documentation on how to do so.

### Task Three

Complete the Voting page and Victors page in voting.tsx and victors.tsx. Your task is to get data from this [API endpoint](https://raw.githubusercontent.com/web-at-berkeley/fa22-frontend-api-endpoint/main/data.json) about the images, scores, and descriptions of each runner and victor. Do not hard-code the values from that json file, and assume it may change in the future.

You should be able to map this data to create cards in the Voting page. You should also keep track of the scores in the Voting page using local state and be able to increment/decrement using your icons (without resetting the other runners' scores). 

You will need to also map the API values you get to create a list of previous winners in the Victors page that, when expanded, shows a short description.


## Submission

**Congratulations!** To submit your project, please make sure your project is in a GitHub repo that is set to private. You will be submitting your code on [Gradescope](https://www.gradescope.com/). If you do not have a Gradescope account, please create one. If you are unable to create one, please email us
immediately. The Gradescope course code is `4V22DJ`. You will see two different assignments: `Frontend Project` and `Backend Project`. _Please only submit to Frontend Technical Project._ You can ignore Backend Technical Project.

The technical project will be due by Wednesday, 9/7 at midnight. We will be unable to respond to clarification emails sent in after then. If you have any questions about the project, please let us know before then (we will be hosting technical project office hours in our club recruitment Discord, which you can join [here](https://linktr.ee/webdevatberkeley)).

Also, this page may potentially keep changing if we get some frequently asked questions, so keep this repository bookmarked and check back on it every now and then! If there are any major changes, we'll make sure to email you about those.
