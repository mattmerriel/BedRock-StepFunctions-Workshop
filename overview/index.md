
Before we get into the **Build** phase of the workshop, it's important to take a moment and look at the problem that we'll be trying to fix throughout this workshop.

This workshop is actually based on a problem statement experience by the **Melbourne AWS User Group** and the original solution implemented to solve it.

The **Melbourne AWS User Group** hosted a monthly meetup in Melbourne and each month they spend the first 15 or so minutes talking about all the new announcements/releases that AWS made over the previous 30 days. This can be a very labour intensive process as there can be dozens or hundreds of announcements made each month (particularly during Re:Invent time). So, the question was asked?

> How can we simplify the generation of the Monthly **What's New** segment each month?

Given that this was November of 2023 and ChatGPT 3.5 had only recently been released, some form of Generative AI solution was a possible solution. So, this is the problem that we need to solve throughout this workshop.

Broken down into it distinct parts, we need to automate:
1. Fetching all of the AWS "What's New" announcements
2. Work out if any of them relate to a new product/service being launched in the Sydney or Melbourne Regions
3. Work out if the announcement would be of interest to the general attendees of the User Group.
4. Generate a slide Pack to present on the night of the User Group.

In the next section, we'll focus on setting up your local machine with the tools required to solve each of these tasks as well as get a project skeleton setup so we have somewhere to start work.

To move to the next section, [here](../Prepare-Local-Development-Environment/index.md).