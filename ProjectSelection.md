# No Name Nomads

## Projects Considered

1. [Blockly](https://developers.google.com/blockly)
   - Project Review Links: [Andrew Scheiner](students/Andrew_Scheiner/Blockly.md)
   - Project Exploration Links: [Mackenzie Hughes](students/Mackenzie_Hughes/Blockly.md), [Chloe Schnydman](students/Chloe_Schnydman/candidate3.md), [Andrew Scheiner](students/Andrew_Scheiner/Blockly.md)
2. [Internet Archive](https://archive.org)
   - Project Review Links: [Long Bui](students/Long_Bui/ProjectReivew/InternetArchived%20-%20ProjectReview.md), [Mackenzie Hughes](students/Mackenzie_Hughes/InternetArchive.md), [Quang Phung](students/Quang_Phung/InternetArchive.md)
   - Project Exploration Links: [Mackenzie Hughes](students/Mackenzie_Hughes/InternetArchive.md), [Quang Phung](students/Quang_Phung/InternetArchive.md)
3. [Mermaid](https://mermaid.js.org)
   - Project Review Links: [Mackenzie Hughes](students/Mackenzie_Hughes/Mermaid.md), [Quang Phung](students/Quang_Phung/Mermaid.md), [Trang Vu](students/Trang_Vu/mermaidJS.md), [Pranav Mishra](students/Pranav_Mishra/Mermaid.md), [Shahir Ahmed](students/Shahir_Ahmed/mermaid.md)
   - Project Exploration Links: [Mackenzie Hughes](students/Mackenzie_Hughes/Mermaid.md), [Trang Vu](students/Trang_Vu/mermaidJS.md), [Pranav Mishra](students/Pranav_Mishra/Mermaid.md), [Shahir Ahmed](students/Shahir_Ahmed/mermaid.md)

## Install Spikes

### Blockly

- Responsible Team Members
  - Andrew Scheiner
- User Install Spike
  - Installation Documents
    - [Blockly Code Labs - Getting Started](https://blocklycodelabs.dev/codelabs/getting-started/index.html?index=..%2F..index#0)
    - [All Blockly Codelabs](https://blocklycodelabs.dev/)
    - [What Is Blockly - Getting Started](https://developers.google.com/blockly/guides/get-started/what-is-blockly) 
  - Download/Demo Sites/Repos
    - [Blockly Code Labs - Getting Started](https://blocklycodelabs.dev/codelabs/getting-started/index.html?index=..%2F..index#0)
  - Summary
    - While Blockly is primarily for developers to contribute to, there must be a way for sites like Scratch and code.org to use it. After some searching, I found a “Getting Started with Blockly” page which links to a “codelab” page. This page is a step-by-step guide for teaching users how to modify and customize a web app to include the Blockly visual programming libraries. The guide goes through the process of building a web app for programming buttons to make sounds. All users need is browser access, a text/code editor, and some basic HTML programming knowledge. Blockly code is easily available for copy/paste for users and the behind-the-scenes concepts of Blockly are hidden (that’s for the developers). First, users must clone the “blockly-samples” Github repo. Next, users will follow several steps to add Blockly libraries, create/load/manage a workspace, create custom code blocks, and generate/run Javascript code. Overall, I found the user experience to be very successful and manageable. The getting started guide was a bit tricky to find, but it was readable and user-friendly.

- Developer Install Spike
  - Installation Documents
    - [Contributing - Getting Started](https://developers.google.com/blockly/guides/contribute/get-started)
    - [Contribute to Blockly Core (Main Blockly Repo)](https://developers.google.com/blockly/guides/contribute/core)
  - Repository Links
    - [Fork](https://github.com/andrewscheiner53/blockly)
    - [Upstream](https://github.com/google/blockly)
  - Summary
    - My experience installing Blockly seemed very simple at the start but ended up giving me some difficulty. The installation document I linked was very straightforward, giving developers instructions for installing Git and Node, and how to clone and create a fork for Blockly’s main repository (called “core”). Developers could also work off Blockly’s “samples” repo as well if they desired. I had no issues creating a fork, cloning my fork, and the npm install step worked well. However, where I ran into problems was when following the next steps, contributing to Blockly “core”. I was unable to run npm run start or npm run build successfully, and the error stated that I did not have Python installed. This was strange to me because I have several versions of Python installed, moreover, when running ‘python –version’ in my computer’s terminal, I realized I needed to download Python specifically from the Microsoft store. After doing this, I was frustrated to learn that even installing Python still did not solve the issue. So overall, the process of cloning a fork of Blockly and setting up npm went flawless but trying to run any npm run commands at Blockly’s root were so far unsuccessful. 

### Internet Archive

- Responsible Team Members
  - Mackenzie Hughes
- User Install Spike
  - Installation Documents
    - [Installation Documents/website](https://openlibrary.org/)
  - Download/Demo Sites/Repos
    - no demo
  - Summary
    - To access Internet Archive’s Open Library project as a user, all you have to do is head over to the above website, where you can make an account and immediately start checking out e-books, or make a request to a library near you with a physical copy. As a guest, you can also search books to see inventory. The documentation for users is very clear and straightforward. The website is the final product, and doesn’t require anything other than an internet browser to connect. As you navigate the website, documentation on how to use the website is apparent but not overbearing. You are free to click on books and search for titles, but in order to access any e-books or make requests, you are prompted to log in or create an account. I did not encounter any difficulties, and I think this would be fairly easy for any user to access. The site also has a language bar in the top corner, which allows the site to be translated into about 15 languages.


- Developer Install Spike
  - Installation Documents
    - [Forking & Cloning](https://github.com/internetarchive/openlibrary/wiki/Git-Cheat-Sheet#forking-and-cloning-the-open-library-repository)
    - [Installation Guide (README.md)](https://github.com/internetarchive/openlibrary/blob/master/docker/README.md)
    - [Creating a new SSH passkey](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
    - [Adding passkey to Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
  - Repository Links
    - [Fork](https://github.com/hughesmac/openlibrary)
    - [Upstream](https://github.com/internetarchive/openlibrary)
  - Summary
    - The setup process was very easy, mostly due to good documentation. The installation guidewas up to date and let me know that I needed to update my Docker. While that was updated, I forked and cloned the repository. I ran into an issue as I was cloning regarding my public SSH key. Helpfully, the guide provided a [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) which helped me resolve the issue within a few minutes. That was the only real issue I faced, and I proceeded with the docker commands to create an image and get it up and running using Docker. I was able to access the website on localhost:8080, as the directions had said. The teardown instructions were also equally helpful, and I closed the project without issue. I enjoyed that the documentation had frequently reported issues for set up, so I didn’t feel confused or lost at any point. Then, I had a look at the code in VsCode, and was pleased to see that it was well organized. I had a look at some of the issues on the tracker, and tried to navigate to where I thought they would be located based on what was reported in the issue. I felt that I was successful, and was pleased to see that the code was neat, and had appropriately named variables that improved overall readability. It did not take me long at all to get this project up and running, and I felt that it was a positive experience that would not make me nervous about returning.

### Mermaid

- Responsible Team Members
  - Quang
- User Install Spike
  - Installation Documents
    - [Install Document](https://mermaid.js.org/intro/)
  - Download/Demo Sites/Repos
    - No demo
  - Summary
    - To access the Mermaid project, all you must do is visit the official Mermaid website. From there, you can view the documentation, try live demos, and explore how to create diagrams directly in your browser. You don’t need any special installation as a user, and the site provides clear guidance on syntax and implementation. The documentation is concise and easy to follow, making it approachable for users of any experience level. Users can use Mermaid for flowcharts, sequence diagrams, and other visualizations with just a browser. Interactive examples are embedded directly in the documentation, helping users quickly learn how to construct diagrams. I found navigating and using the site to be very intuitive, with no technical issues encountered. Additionally, Mermaid offers language support, ensuring accessibility for a global audience.
- Developer Install Spike
  - Installation Documents
    - [Contributing Guide](https://mermaid.js.org/community/contributing.html)
    - Requirements (Volta, Node.js, pnpm)
    - Installation Guide
  - Repository Links
    - [Fork](https://github.com/QuangPhung15/mermaid)
    - [Upstream](https://github.com/mermaid-js/mermaid)
  - Summary

    - To set up the development environment for Mermaid, several key tools are required. First, Volta is used to manage Node.js versions, ensuring compatibility across different machines and projects. Installing Node.js through Volta is simple with the command `volta install node`, providing an easy way to handle version control. Additionally, the pnpm package manager is required, which can also be installed via Volta using the command `volta install pnpm`. Pnpm is preferred over npm for this project due to its faster performance and efficient disk space usage. These tools together create a stable and manageable environment for developing and contributing to Mermaid.

    - Mermaid is an active and growing project, and the community is always looking for new contributors. To get started, I first referred to the contribution guideline, which outlined the basic requirements for setting up the development environment. I installed Volta to manage Node.js versions, ensuring compatibility across different setups. After that, I used Volta to install both Node.js and the pnpm package manager, which the project uses for package management.

    - The setup process was straightforward. After cloning the repository, I navigated to the project directory and ran npx pnpm install to install all the necessary dependencies as Volta’s direct support for pnpm is not yet available). The project was up and running quickly after running pnpm test, which confirmed that everything was correctly installed. The documentation also provided a clear way to manually test the project in the browser by opening the dist/index.html file.

    - The project uses ESLint for linting, and the recommendation to install editor plugins for real-time lint feedback was very helpful. Running pnpm lint quickly identified any issues in the code. For those with release permissions, the process to update and publish a new version was well-documented, with a simple command to publish the package to npm.

    - Overall, the development setup was well-documented, and I felt confident working on the codebase. The guide helped me navigate through common tasks like testing, linting, and even publishing a release for contributors with the right permissions. I found the whole process intuitive and would encourage others to contribute.


## Project Rankings

Project Name | Community | Complexity | Activity | Approachability | Appeal
-------------|-----------|------------|----------|-----------------|--------
P1           | 1         | 2          | 1        | 2               | 2
P2           | 2         | 1          | 2        | 1               | 2
P3           | 2         | 3          | 2        | 2               | 3

- Rationale
  - **Community:** When our group discussed community, our group was looking for a college friendly community. Where the community would have a group of college students like us that are working to achieve the same goal. Out of all the types of community interfaces some of the group members prefer the Google Group and others were okay with the other styles of chats we saw. We also rationalized a reasonable time frame that we should expect to receive a response if we were to send a message or ask a question. That time frame would be around at least a day or two so we can efficiently get issues and pull requests moving. Our rationale with Community stands that it is important but we can live with a community that isn't as strong but still can lead us on the right path, we think the tradeoff between Community and these other categories is less where we might vote in favor of another category to ensure a project is more fit for our group.

  - **Complexity:**  The conversation about complexity consisted of the intensity of first issues where the difficulty was similar but different throughout the projects we have observed. Mermaid appeared to be the most complex in regards to where to begin and initially helping out, where Blockly and Internet Archive were more of our group's speed. All three of the projects explored had tools and languages that our group has dealt with or know something about. We established the complexity rankings on these principles and each member who ran through the spikes section was certain on where each project stood on levels of difficulty, which made it easier for the group to come to a decision on each rank. We decided that complexity was important in the selection process because as a group we can't select a project that would be too difficult leaving us at stalemates with issues and not progressing the project. It would just be hurting us and the project by not moving forward in solving issues.

  - **Activity:**  When Activity was discussed, our group circled around the idea of response and pull request rates. We had a longer group discussion about this topic, where it was important that messages and pull/merge requests getting recognized. Especially with what we are trying to accomplish this semester as a group we need an an active project to meet deadlines for the class and within the project. Another part of Activity that we discussed was the rate of issues being posted, so that our group would have ample work to partake in. We consider that Activity was high up on the ranking scale, because to further along said project we are going to need an active community and updates to help us help them.   

  - **Approachability:**  The primary concern with a project's approachability is that there are multiple first issues and proper documentation that won't mislead new beginners. We mentioned that the idea of Blockly is very approachable but the installation process was troublesome and lacking in good first issues. Internet Archive was a strong candidate for this category where installation documentation provided lots of help and first issues were not overwhelming. Mermaid was similar to problems with Blockly in regards to no good first issues and installation troubles. We said the Approachability was a big factor in picking projects because of how quickly we are to rule out projects that do not fit the comfortability of our own skill sets and stray new developers away.

  - **Appeal:**  Our groups appeal came from an idea of familiarity, such as blockly was a project we all kind of did when we were younger in grade school. More then half the group said that they had seen or used an application like blockly in their early coding years before we even decided to become coders. All the projects we observed used languages that we have all seen which boosted the appeal to most of the projects. Internet Archive had the most upside initially because of our groups familiarity with all the tools and tech being applied. Our group consensus on Appeal wasn't as centralized compared to comparative categories, such that our group was created on the stragglers that were not head over heals for one particular project but willing to expand our horizons on other projects. Our group is willing to try multiple project which labels Appeal as not as big of a priority when selecting a project.

## Project Selection

- Internet Archive
- Rationale
  - Our group came to the conclusion on Internet Archive for a couple reasons. First, we were neck and neck with Blockly and Internet Archive but Internet Archive received better rankings in Complexity and Approachability. Those two categories were at top priority when our group was deciding on a project. Secondly, there were installation issues on Blockly which made the choice a lot more clear because it was not a simply fix. So we decided to step away from Blockly even though it was a close race. Mermaid wasn't really in the cards and was ranked last in our group's ranks.
- Install Estimates
  - User install took roughly about 5 minutes.
  - Developer install took around 1 hour.
- Knowledge Gaps
  - Our group would need to do some touching up on Vue and learn more about Less and infogami.
    - Less 
    - Vue
    - infogami
- Concerns
  - The group's general concerns are just about the activity of this project where if we are in need of assistance, we would hope for a timely response or enough issues to work on throughout the semester.

 19 changes: 19 additions & 0 deletions19  
teams/CSSteam/README.md
Viewed
Original file line number	Original file line	Diff line number	Diff line change
@@ -0,0 +1,19 @@
