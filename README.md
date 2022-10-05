# Jupyter Coding Challenge

At aspaara a squad of superheroes work on giving superpowers to planning teams.
As part of this, we give insights into data through our product dashboar – a
true super-vision superpower. Join forces with us and generate the insights
of the future!

![aspaara superhero](aspaara_superhero.png)

## Goal

Create a simple notebook that allows a planner to get insights into client and
planning information.

You will find the corresponding data to display in `planning.json`, which
contains around 10k records.

## Requirements

The notebook should

* give an overview of the data
* provide in-depth statistics for at least one of the following attributes:
  * booking grade
  * office city
  * skills
  * industry
* give insights into what you find most noteworthy ;)

## Data Model

* ID: integer (unique, required)
* Original ID: string (unique, required)
* Talent ID: string (optional)
* Talent Name: string (optional)
* Talent Grade: string (optional)
* Booking Grade: string (optional)
* Operating Unit: string (required)
* Office City: string (optional)
* Office Postal Code: string (required)
* Job Manager Name: string (optional)
* Job Manager ID: string (optional)
* Total Hours: float (required)
* Start Date: datetime (required)
* End Date: datetime (required)
* Client Name: string (optional)
* Client ID: string (required)
* Industry: string (optional)
* Required Skills: array of key-value pair (optional)
* Optional Skills: array of key-value pair (optional)
* Is Unassigned: boolean (optional)

## Tech Stack

* Python
* Jupyter notebook (or similar)
* any other python library you want to use

## Submission

* Please fork the project, commit and push your implementation and add
  `sundara.amancharla@aspaara.com` as a contributor.
* Please update the README with any additional details or steps that are
  requried to run your implementation.
* We understand that there is a limited amount of time, so it does not have to
  be perfect or 100% finished. Plan to spend no more than 1-2 hours on it.

For any additional questions on the task please feel free to email
`sundara.amancharla@aspaara.com`.

We are looking forward to see what insights you can gain from the data!
