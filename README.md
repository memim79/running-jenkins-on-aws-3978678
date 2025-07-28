# Running Jenkins on AWS: Deploying and Managing Jenkins on Cloud Infrastructure

This is the repository for the LinkedIn Learning course `Running Jenkins on AWS: Deploying and Managing Jenkins on Cloud Infrastructure`. The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

## Course Description

Learn how to create a Jenkins environment using the cloud-based servers of AWS. In this course, instructor Michael Jenkins covers steps for setting up Jenkins, creating a build environment, connecting to code repositories with webhooks, using a deployment service, and shutting down AWS resources. First, Michael shows you how to create a Jenkins controller instance, including how to configure a security group, an NGINX reverse proxy, and the Jenkins automation service. Next, he takes you through creating a build environment and connecting the Jenkins controller to the build server. Michael explains what a webhook is, demonstrates how to create and test one in GitHub, and shows how to use a webhook to trigger an automated deployment with AWS Lambda. Finally, Michael discusses how to stop or remove AWS resources.

## Course Structure

This repository is organized into directories that correspond to the videos and exercises in the course. Each chapter has its own directory, and within each chapter directory are subdirectories for each video or exercise.

The course is organized into the following chapters:

| Chapter | Description |
| --- | --- |
| **0: Introduction** | Course overview and prerequisites |
| **1: Setting Up Jenkins** | Deploy the resources needed for a primary Jenkins server |
| **2: Create a Build Environment** | Deploy the resources needed to set up a build agent |
| **3: Connect Jenkins with Webhooks** | Plan a CI/CD pipeline that connects a Jenkins job to a code repository |
| **4: Deploy Code to AWS Lambda** | Apply the build environment by deploying code to AWS Lambda |
| **5: Shut Down AWS Resources** | Best practices for decommissioning resources |
| **6: Conclusion** | Course summary, key concepts review, and next steps for continued learning |

## Installing

1. To use these exercise files, you must have the following accounts in place:

    - **GitHub**, a web-based platform that uses Git for version control and collaboration on software development projects.
    - **Amazon Web Services**, a cloud computing platform that provides a wide array of on-demand services

1. Clone this repository to your local machine using your system's terminal or using a GUI tool like [SourceTree](https://www.sourcetreeapp.com/) or [GitHub Desktop](https://github.com/apps/desktop).
1. See the README file in each directory for specific instructions related to the corresponding lesson.

## Instructor

Michael Jenkins, Lead Software Engineer

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/michael-jenkins).

[lil-course-url]: https://www.linkedin.com/learning/running-jenkins-on-aws-deploying-and-managing-jenkins-on-cloud-infrastructure
[lil-thumbnail-url]: https://media.licdn.com/dms/image/v2/D4E0DAQG0r7-qFsC2SA/learning-public-crop_675_1200/B4EZg4SNTOHoAY-/0/1753290954650?e=2147483647&v=beta&t=5qXC2cWevHWwseDS3vED62AV7AIuUNiKy48BcM5AP1Q

<!-- FooterStart -->
---
[00_01 Intro →](ch0_introduction/00_01_intro/README.md)
<!-- FooterEnd -->
