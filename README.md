# BlogPost

## Built By [Barbara Mutindi](https://github.com/barbaramutindi/)

## Description
An application that allows users to use that one minute wisely. The users will submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.


## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like to:
* See the pitches other people have posted.
* submit a pitch in any category.
* be signed in for me to leave a comment
* view the pitches I have created in my profile page.
* comment on the different pitches and leave feedback.

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display pitch categories | **On page load** | List of various categories of pitches |
| Display tabs with  category | **On Tab link click** | Clickable links to open pitches by category |
| Display profile | **Click profile page** | Redirected to a page with your profile |
| Display pitches | **On page load** | Each pitch displays author, title, pitch, date comment tab |
| To add a pitch  | **Click an add pitch** | Redirected to the pitch collection form|

## SetUp / Installation Requirements
### Prerequisites
* python3.8
* pip
* virtualenv

### Cloning
* In your terminal:

        $ git clone https://github.com/barbaramutindi/Blog-Post-Heroku.git
        $ cd peech

## Running the Application
* Creating the virtual environment

        $ python3.8 -m venv --without-pip virtual
        $ source virtual/bin/env
        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Flask and other Modules

        $ see Requirements.txt

* To run the application, in your terminal:

        $ chmod +x start.sh
        $ ./start.sh

## Testing the Application
* To run the tests for the class files:

        $ python3.8 manage.py test

## Technologies Used
* Python3.8
* Flask

## License & Copyright
© Barbara Mutindi

Licensed under [MIT License](LICENSE)