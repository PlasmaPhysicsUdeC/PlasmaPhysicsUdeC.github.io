# UdeC Plasma Physics Group - webpage

## What is this repository?

This project holds the source code for the [webpage](https://plasmas-udec.netlify.app) of the Plasma Physics Group from the [Universidad de Concepción](www.udec.cl), Chile.

Any change on the master branch of this repository is automatically reflected on the webpage, which is directly deployed from github to netlify.

We used the [starter-academic](https://github.com/wowchemy/starter-academic) template freely provided by [**Wowchemy**](https://wowchemy.com) for the [Hugo](https://github.com/gohugoio/hugo) website building framework.

## How do I make changes to the webpage?

If you want to propose some change, you are most welcome to fork the repository and make a pull request. However, for questions regarding on how to implement such changes, please refer to the vast [official documentation](https://wowchemy.com/docs/) of the template used.

## How to deploy locally?

After some modifications, you will probably want to deploy and view the webpage locally before submitting the changes. To this end, a simple shell script called `view.sh` was put in the root of the repository. Executing the script will run `hugo server` and deploy the webpage to `localhost` on the port `1313` unless the port is already taken. Then, you can view the local version of the webpage by visiting `localhost:1313` on your favorite web browser.

## Requirements

To deploy the webpage locally, you will require **Hugo extended** (releases can be found [here](https://github.com/gohugoio/hugo/releases)).

## Final notice

The website is still under construction :)
