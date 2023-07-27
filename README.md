<a name="readme-top"></a>

<!-- PROJECT HEADER-->
<br />
<div align="center">
  <h1 align="center">
    Warbler!
  </h1>
  <p>A twitter clone.</p>
</div>


## Built With

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)



<!-- USAGE EXAMPLES -->
## Usage

<h1>DEMO VIDEO GOES HERE</h1>



<!-- GETTING STARTED -->
## Getting Started

## Installation

1. Clone the repo
   ```sh
   git clone git@github.com:shavinski/flask-warbler.git
   ```
2. Create a virtual environment and download requirements.txt
   ```sh
    python3 -m venv venv
    source venv/bin/activate
    pip3 install -r requirements.txt
   ```
3. Set up a database with dummy data (PSQL)
   ```sh
   psql
   CREATE DATABASE warbler;
   (ctrl+d or cmd+d) 
   python3 seed.py
   ```
4. Add a .env file
  ```sh
  SECRET_KEY=(any secret key you want)
  DATABASE_URL=postgresql:///warbler
  ```
5. Run on your local server
  ```sh
  flask run 
  ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [x] Fix log-out logic
- [x] Fix user profile
    - [x] Add location
    - [x] Add a bio
    - [x] Add header image
- [x] Add profile info for the follower page
    - [x] Location appears on follower card
    - [x] Bio appears on follower card
    - [x] Header image appears on follower card   
- [x] Add Likes
- [x] Implement profile edit 
- [x] Add tests
    - [x] test user model
    - [x] test user views
    - [x] test message model
    - [x] test message view
- [ ] Custom 404 page
- [ ] Dry up authorization
- [ ] Dry up templates
- [ ] Add Private accounts 



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Email: shavinski.jakob@gmail.com

LinkedIn: https://www.linkedin.com/in/jakob-shavinski/

<p align="right">(<a href="#readme-top">back to top</a>)</p>


