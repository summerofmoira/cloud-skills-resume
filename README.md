# Cloud Skills Resume

This project is based on [Resume](https://startbootstrap.com/theme/resume/), a resume and CV theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/). This theme features a fixed sidebar with content sections to build a simple, yet elegant resume.

## Download and Installation
- [Fork this repository](https://github.com/757colorcoded/cloud-skills-resume/fork)
- Clone your fork

## Usage

### Basic Usage

* After downloading, simply edit the HTML, CSS, and asset files included with `dist` directory.
* To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Hosting
This repository assumes you'll be using AWS to host this site. You can follow AWS' instructions to [Use an Amazon CloudFront distribution to serve a static website](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started-cloudfront-overview.html).

### Deploying
Once you're all set up, you can deploy this site using the provided GitHub Actions configuration file.

Change the value of the following variable in your [deploy.yaml](.github/workflows/deploy.yaml) file:
```shell
FIRST_NAME: Guillermo
```

You'll need to create the following repository secrets to successfully deploy this site to AWS:
```shell
AWS_S3_BUCKET # the bucket to which you'll be deploying
AWS_ACCESS_KEY_ID # your access key ID
AWS_SECRET_ACCESS_KEY # your secret access key
AWS_REGION # the region to which you'll be deploying
AWS_CLOUDFRONT_DISTRIBUTION_ID # the distribution ID you'll be using
```

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/757colorcoded/cloud-skills-resume/issues) here on GitHub.

## About Start Bootstrap

Start Bootstrap is an open source library of free Bootstrap themes and templates. All of the free themes and templates on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

- <https://startbootstrap.com>
- <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](https://davidmiller.io/)**.

- <https://davidmiller.io>
- <https://twitter.com/davidmillerhere>
- <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## License

Code released under the [MIT](https://github.com/757colorcoded/cloud-skills-resume/blob/main/LICENSE) license.
