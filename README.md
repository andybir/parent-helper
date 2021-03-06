# Project Overview

## Project Schedule

|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Build out backend | Complete
|Day 2| Begin front end work - create components, basic layout | Complete
|Day 3| Continue Front end work - logic, routing | Complete
|Day 4| ICM, begin CSS | Complete
|Day 5| Complete CSS, MVP  | Complete


## Project Description

Parent Helper is a resources for parents living in NYC where other parents can recommend activites, handymen, local news and parenting advice.

## Wireframes

https://ninjamock.com/s/VLLXCFx

## Priority Matrix

[Parent Helper Priority Matrix](readme-assets/ParentHelperPrioMrtx.pdf)

### MVP/PostMVP - 5min

#### MVP 

- Allow user to browse topics
- Create posts, comment on posts

#### PostMVP 

- Search for topics
- create new topics (admin will create all topics for MVP)
- auth

## Architectural Design

[Parent Helper Component Hierarchy](readme-assets/ParentHelperCompHier&#32;(2).pdf) 

## ERD

[Parent Helper ERD](readme-assets/ParentHelperERD&#32;(2).pdf)

## UI Components

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| Nav | This will render the header include the nav | 
| Home | choose browse topic, search topic or create a post | 
| Topic List | will list all topics to choose from | 
| Topic Search | allow user to enter search terms to look up topics of interest | 
| Post List | browse listing of posts based on chosen topic | 
| Post | a comment on a particular topic with ability to reply | 
| Create Post | choose from a list of topics, create a new post | 


## Timeframes
| Component | Priority | Estimated Time | Actual Time |
| --- | :---: |  :---: | :---: |
| Build out back end | H | 4hrs| 4hrs |
| Create MVP components, component layout | H | 3hrs | 2hrs |
| React routing | H | 4hrs | 3hrs |
| Front end logic | H | 8hrs | 12hrs |
| Test for ICM | H | 4hrs | 2hrs |
| CSS | H | 8hrs | 6hrs |
| PMVP | H | 4hrs | ?? |
| Total | H | 35hrs| 29hrs | 

## Helper Functions

| Function | Description | 
| --- | :---: |  

## Additional Libraries
 
| Library | What it Does | 
| --- | :---: |
| material-ui | allows for importing clean forms with simple animations |  
| react-alert | allows for nicely styled button pop up alerts |  

## Code Snippet
```
    const [formValue, setFormValue] = useState('')

    <TextField
                    value={nameValue}
                    name='name'
                    onChange={(e) => setNameValue(e.target.value)}
                    label='Name'
                    placeholder='Name'
                    className='name-box'
                    margin='normal'
                    variant='outlined'
                />
```
## Change Log

1.1 making edits to clean up code/comments etc.

## Issues and Resolutions
Issue 1. when submitting comment or post, does not render on page without reloading from previous page.  Hitting refresh breaks app
Resolution: ??