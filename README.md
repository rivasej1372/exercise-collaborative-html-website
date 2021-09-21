# Making a website as a team (Git collaboration)

Practice your skills in GIT while developing a typical website.

Each student works on a different file, for a different part of the website, and the most senior can work as Team Leader (for integration and deployment), unless the teacher prefers to be the team leader of the whole class. The Html-Template-Engine library will take care of putting all the pieces together.

## 📝 Instructions

<img align="right" height="400" src="https://github.com/breatheco-de/exercise-collaborative-html-website/blob/master/website1/designs/guide.jpg?raw=true" />

1. The Team Leader should fork this repository on github.com and [invite other collaborators to the repo](https://github.com/breatheco-de/exercise-git-collabration/blob/master/iOBmU5zYqA.gif). Give access to the others on the newly forked GitHub repository to other team members, and make sure they are cloning from this new repository, not the original!

2. We are going to be building [this design](https://raw.githubusercontent.com/breatheco-de/exercise-collaborative-html-website/master/website1/designs/thumb.jpg), and [this is how you can split with the students](https://github.com/breatheco-de/exercise-collaborative-html-website/blob/master/website1/designs/guide.jpg?raw=true)

3. Each contributor will have to clone the new forked repository and develop a part of the website that is coordinated with the group; each project is divided in pieces inside the **templates/** directory (located in website/templates). Once everyone has their editor open, run the project in the terminal with this command:

```bash
npx http-server --yes -c-1
```

You will be given an option to open in browser, and have options to view the new site, what it should look like, and a reference to each part of the page. If you receive an error, wait a moment and refresh.

4. **To start, each member should put their name in the file they have been assigned, push back to the repository, and pull to see the others changes. Maintaining clear communication about the files being used will make the project run smooth :)**

5. Once everyone understands how to modify their part of the project and push, use the seach feature and examples within https://getbootstrap.com/ to quickly build using bootstrap components, then modify accordingly.

## 🌱  How to start this project

This project comes with the necessary files to start working, but you have two options to start:

Gitpod: 

a) Use Gitpod (recomended): open this link in your browser to clone it with gitpod: https://gitpod.io#https://github.com/breatheco-de/exercise-collaborative-html-website.git

b) You can clone this repository on your local computer:

```sh
$ git clone https://github.com/breatheco-de/exercise-collaborative-html-website.git
```

In order to watch the website live run the following command:

```bash
$ npx http-server --yes -c-1
```

## Deploy the website

Use Vercel, Netlify or Github pages to deploy the website to the team URL (for example: `https://mysuperteam.zeit.sh`).

## Delivery

Everyone delivers the same repo as solution.

## Complementary info

The [Html-Template-Engine library](https://github.com/alesanchezr/html-template-engine) is being used as template engine for building the landing page.

