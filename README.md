

<h3 align="center">
	Lambda function for image analysis with AWS Rekognition
</h3>
<p align="center">
Automated <b>image analysis</b> with machine learning using a <b>lambda function</b> with a <b>translation service</b> to translate the answer in Portuguese Brazil (pt-BR).
</p>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/robertosousa1/lambda-image-analysis-with-aws-rekognition.svg">
  
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/robertosousa1/lambda-image-analysis-with-aws-rekognition.svg">
  
  <a href="https://www.codacy.com/app/robertosousa1/lambda-image-analysis-with-aws-rekognition?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=robertosousa1/lambda-image-analysis-with-aws-rekognition&amp;utm_campaign=Badge_Grade">
    <img alt="Codacy grade" src="https://img.shields.io/codacy/grade/70c8e79c83b442278f6c276ebf117ae4.svg">
  </a>
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/robertosousa1/lambda-image-analysis-with-aws-rekognition.svg">
  <a href="https://github.com/robertosousa1/lambda-image-analysis-with-aws-rekognition/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/robertosousa1/lambda-image-analysis-with-aws-rekognition.svg">
  </a>
  
  <a href="https://github.com/robertosousa1/lambda-image-analysis-with-aws-rekognition/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/robertosousa1/lambda-image-analysis-with-aws-rekognition.svg">
  </a>
</p>

<p align="center">
  <img src="https://res.cloudinary.com/robertosousa1/image/upload/v1587516279/github-readme/ezgif.com-optimize_cykbc4.gif" alt="demo-web" height="385">
</p>

<p align="center">
<a href="#rocket-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#ballot_box_with_check-prerequisites">Prerequisites</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#up-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#pencil2-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## [](#technology):rocket: Technology
-  **[AWS Lambda](https://aws.amazon.com/pt/lambda/)** — Allows you to run code without provisioning or managing servers.
-  **[Serverless Framework](https://serverless.com/)** — Gives you everything you need to develop, deploy, monitor and secure serverless applications on any cloud.
- **[AWS Rekognition](https://aws.amazon.com/pt/rekognition/)** — Automation of image and video analysis with machine learning.
- **[AWS Translate](https://aws.amazon.com/pt/translate/)** — Neural machine translation service


## [](#prerequisites):ballot_box_with_check: Prerequisites
-   [Node.js](https://nodejs.org/en/)
-   [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/pt-BR/docs/install)
- [AWS CLI](https://aws.amazon.com/pt/cli/)
- [Serverless Framework](https://serverless.com/)

## [](#getting-started):up: Getting started

-   Clone this repo
-  Enter the folder `lambda-image-analysis-with-aws-rekognition`
-  Run `yarn` or `npm install` to install the dependencies
- Run `sls deploy` or `serverless deploy` to upload the lambda function to AWS
- Access the **endpoint** informed in the terminal
- After the endpoint in the browser, insert the query string `?imageUrl=` then insert the address of the image on the web you want to analyze
## [](#how-to-contribute):pencil2: How to contribute

-   Make a fork;
-   Create a branck with your feature:  `git checkout -b my-feature`;
-   Commit changes:  `git commit -m 'feat: My new feature'`;
-   Make a push to your branch:  `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## [](#license):memo: License
This project is under the MIT license. See the [LICENSE](https://github.com/robertosousa1/lambda-image-analysis-with-aws-rekognition/blob/master/LICENSE) for more information.

----------

Made with by Roberto Sousa  👋  [Get in touch!](https://www.linkedin.com/in/robertosousa01/)


