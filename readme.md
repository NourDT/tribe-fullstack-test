# Full-stack Developer test

Make sure you read **all** of this document carefully, and follow the guidelines in it.

## Context

There's a folder in this repo that contains wireframe for a simple listing page. User should be able to search in that page and click on a title to view the content of it. Please make a simple and beautiful page that get the job done. 

## User Story

1. User opens the page and could see a list of titles 
2. User can use the search box to filter titles. 
3. User can click onto a title to view it
4. User is able to leave comments on the content page. 

## Requirements

### Functionality

- The **frontend** part should be a single page application rendered in the frontend and load data from restful API (**not** rendered from backend).
- Your **backend** and database/storage should be created and deployed to AWS - you should be able to build all of the logic for this single page app in [lambda functions](https://aws.amazon.com/lambda/). We have no prefrence for what type of storage you choose, RDS, S3 or others so feel free to pick whatever works best for this use case.

### Tech stack

- Backend oriented
    - Use [Lambda Functions](https://aws.amazon.com/lambda/) &  [API Gateway](https://aws.amazon.com/api-gateway/) for the backend.
    - Use any **language** you like.
    - Use any any storage system for this task, even a static JSON file storage would do it.
- Frontend oriented
    - Use ([React](https://reactjs.org/) to build the front-end
    - Layout has to be responsive 
    - Don't use any CSS Frameworks
    - Use a scaffolding tool such as `create-react-app`
        - Feel free to use any JS frameworks such as React-Router, and packing tools such as Webpack or Parcel etc.

### Bonus

- Write clear **documentation** on how it's designed and how to run the code.
- Provide proper unit test.
- Write good commit messages.
- An online demo is always welcome.
- Use any provisioning tool to auto deploy the entire stack to an AWS account ([Terraform](https://www.terraform.io/), [Serveless](serverless.com))

### Advanced requirements

These are used for some further challenges. You can **safely skip them if you are not asked to do any**, but feel free to try out.
- **Backend**:
    - Provide a complete user auth (authentication/authorization/etc) strategy, such as OAuth.
    - Provide a complete logging (when/how/etc) strategy.
    - Use a NoSQL DB and build a filter feature that can filter records with some of the attributes 
- **Frontend**:
    - Provide an error handling strategy, such as the UI/UX, and different handling for different errors etc.



## What We Care About

Feel free to use any libraries you would use if this were a real production App, but remember we're interested in your code & the way you solve the problem, not how well you can use a particular library.

We're interested in your method and how you approach the problem just as much as we're interested in the end result.

Here's what you should aim for:

- Good use of current HTML, CSS, and JavaScript & performance best practices.
- Solid testing approach.
- Extensible code.

## Q&A

> Where should I send back the result when I'm done?

Fork this repo and send us a pull request when you think you are done. **Deadline is next Wednesday 30th of May.** 

> What if I have a question?

Email nour@tribenow.tv & gorhom@tribenow.tv for any questions. 
