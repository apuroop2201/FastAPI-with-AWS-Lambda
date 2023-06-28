<br/>
<p align="center">
  <a href="https://github.com/apuroop2201/ReadME.md">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">FastAPI with AWS Lambda</h3>

  <p align="center">
     Deployment of FastAPI with AWS Lambda and GitHub Actions Pipeline
    <br/>
    <br/>
    <a href="https://github.com/apuroop2201/ReadME.md"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/apuroop2201/ReadME.md">View Demo</a>
    .
    <a href="https://github.com/apuroop2201/ReadME.md/issues">Report Bug</a>
    .
    <a href="https://github.com/apuroop2201/ReadME.md/issues">Request Feature</a>
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/apuroop2201/ReadME.md/total) ![Contributors](https://img.shields.io/github/contributors/apuroop2201/ReadME.md?color=dark-green) ![Issues](https://img.shields.io/github/issues/apuroop2201/ReadME.md) ![License](https://img.shields.io/github/license/apuroop2201/ReadME.md) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

Creator : Apuroop Pendurthi

Description : Basically,we deploy a simple FastAPI application to AWS Lambda. First we build a FastAPI app and create simple tests. We then go ahead to create a GitHub workflow to ultimately deploy to AWS Lambda. We finish off by configuring AWS API Gateway to access the FastAPI application.

## Built With

Tools Used : Python, FastAPI, AWS Lambda, AWS API Gateway, VS Code, Github

* []()

## Getting Started

Instructions to run Project.


### Prerequisites

1-) Install any code editor (preferably VS Code ).
2-) Create a python virtual Environment and install all the modules existing in requirements.txt file.
3-) Create a simple API Code which is available in main.py
4-) Test the test_core.py code using pytest 
5-) Once done, Build a github Pipeline using the code in main.yml (this is in yaml format)
6-) Have an AWS account, login into it and create an s3 bucket and AWS lambda function in same region, the Lambda function must have runtime in Python 3.7
7-) Change handler name of Lambda function to main.handler to make sure it works fine.
8-) Add additional aws yaml code into main.yml and push all to github to commit. Now a zip file is generated which can be now deployed in AWS Lambda.
9-) Now setup, AWS Access key, access key ID and Default Region in Secrets menu of Github to allow Github to perform actions in AWS Account.
10-) Now, create an API Gateway and once an endpoint is generated, you can use Postman to check the working of the endpoint, basically the endpoint represents the output which we coded in main.py file
11-) So, FastAPI is deployed in AWS lambda and an endpoint is created using AWS API Gateway with Github Actions.

## Usage

Any type of API can be created with this process and AWS lambda which is a serverless function can be used to make this process faster and endpoints can be generated.

## Roadmap

See the [open issues](https://github.com/apuroop2201/ReadME.md/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/apuroop2201/ReadME.md/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/apuroop2201/ReadME.md/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/apuroop2201/ReadME.md/blob/main/LICENSE.md) for more information.

## Authors

* **Apuroop Pendurthi** - *Software Engineer* - [Apuroop Pendurthi](https://github.com/apuroop2201) - *Entire Project*

## Acknowledgements

* []()
* []()
* []()
