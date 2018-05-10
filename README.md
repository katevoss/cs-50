# TODOs

* Change location of configuration file to not be hidden

## Introduction

This is my final project for CS-50, Spring 2018, called "". The purpose of this project is to help a user set up their configuration file so that they can run genomic pipelines through Google Cloud using the Google Genomics Pipelines API. The project design is described in [DESIGN](design) which includes a map of the steps that the script follows and the opportunites for user interaction. 



## How to run

The necessary files 

## Screencast

To view a video of me walking through the steps to run the script, view the youtube link here: #TODO

include your project’s title, your name and year, your dorm/house and concentration, and any other details


### Pre-requisites

To run this project, you must have Git installed locally. For more information, see the Git #TODO

0. Git 
1. Python 2.7
2. Install the Google Cloud SDK from https://cloud.google.com/sdk/downloads
3. Set the Application Default Credentials 
	* To do this, run `gcloud auth application-default login`
4. [Google Billing Project](https://cloud.google.com/billing/docs/how-to/manage-billing-account#create_a_new_billing_account) to pay for storage and compute
5. Run `python setup.py install`

#### Clone locally

For the optimal experience, you should clone this repository and run it locally on your Mac or POSIX-environment laptop.

In your terminal, run the following commands:

```
$ cd ~
$ mkdir kvoss-final-project
$ cd kvoss-final-project
$ git clone <repo url>
$ cd <dir name>
```

#### Python dependencies

This script requires the user to have some specific libraries installed in order to run it. 

To install the required Python libraries, first navigate to this directory locally. Then run this script:

```
$ python setup.py
```

### Run the script

Now is the time to run the script. 

```
$ python create_google_config.py
```



## Troubleshooting

### Are you connected to the internet?

To run this program, you must be connected to the internet.


### Are you running it in Python 2?

As written in the pre-requisites, this program requires Python 2.




This documentation is to be a user’s manual for your project. Though the structure of your documentation is entirely up to you, it should be incredibly clear to the staff how and where, if applicable, to compile, configure, and use your project. Your documentation should be at least several paragraphs in length. It should not be necessary for us to contact you with questions regarding your project after its submission. Hold our hand with this documentation; be sure to answer in your documentation any questions that you think we might have while testing your work.