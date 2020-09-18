# Django based movie recommender system
> https://awesome-movie-recommender.herokuapp.com

![GitHub stars](https://img.shields.io/github/stars/rajaprerak/movie_recommender) 
[![Maintenance](https://img.shields.io/badge/maintained-yes-green.svg)](https://github.com/rajaprerak/movie_recommender/commits/master)
[![Website shields.io](https://img.shields.io/badge/website-up-yellow)](https://awesome-movie-recommender.herokuapp.com/)
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

### Website Preview
#### Home Page
<img src="website_images/HomePage.png" width="900">

#### Detail Page
<img src="website_images/DetailPage.png" width="900">

----

## Installation 📦

>pip install -r requirements.txt

#### Clone

- Clone this repo to your local machine.

#### Run server locally

```shell
$ python manage.py runserver
```
> Go to localhost:8000

---
## Features 📋
* User can register and login.
* User can search through various movies and look through its details.
* User can give rating to the movies.
* User can add movie to their watch list.
* User can get movie recommendation (Recommendation algorithm (Collaborative Filtering) which suggests new movies based on the ratings given by user.)
---

## Algorithm
##### Collabortive Filtering (Recommender Algorithm)
* Collaborative filtering filters information by using the interactions and data collected by the system from other users. It's based on the idea that people who agreed in their evaluation of certain items are likely to agree again in the future.
* When we want to find a new movie to watch we'll often ask our friends for recommendations. Naturally, we have greater trust in the recommendations from friends who share tastes similar to our own.
* Collaborative-filtering systems focus on the relationship between users and items. The similarity of items is determined by the similarity of the ratings of those items by the users who have rated both items.
* There are two types of collaborative filtering
    * **User-based**, which measures the similarity between target users and other users.
    * **Item-based**, which measures the similarity between the items that target users rate or interact with and other items.
    > I have used **user based** collaborative filtering in this project.
     
     
  ---

## Contributing 💡


#### Step 1

- **Option 1**
    - 🍴 Fork this repo!

- **Option 2**
    - 👯 Clone this repo to your local machine.


#### Step 2

- **Build your code** 🔨🔨🔨

#### Step 3

- 🔃 Create a new pull request.

## Team ✨

| <a href="https://rajaprerak.github.io" target="_blank">**Prerak Raja**</a>
| :---: |
| [![Prerak Raja](https://github.com/rajaprerak.png?size=100)](https://rajaprerak.github.io)    
| <a href="https://github.com/rajaprerak" target="_blank">`github.com/rajaprerak`</a>


## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**

                                                                                                                                                                                                                                                                        
