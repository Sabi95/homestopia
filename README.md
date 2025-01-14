# 🏡 Project Name

A marketplace web application with a concentration on sharing homestay experiences. Find a family to host you anywhere in the world, or host your own traveller from abroad.

<img width="1248" alt="2022-12-05 (15)" src="https://user-images.githubusercontent.com/114859704/205580308-82662bed-0f37-4e81-9e26-f7f1f493ed5a.png">
<img width="1248" alt="2022-12-05 (16)" src="https://user-images.githubusercontent.com/114859704/205580233-c9ea4a6a-a706-493d-898b-01113c380d03.png">
<img width="1248" alt="2022-12-05 (22)" src="https://user-images.githubusercontent.com/114859704/205580442-9dd1bb99-3420-4d49-9ff0-02e58e670f6d.png">
<img width="1248" alt="2022-12-05 (18)" src="https://user-images.githubusercontent.com/114859704/205580262-a6c97b9f-4404-4d40-905a-057e647b2ba0.png">
<img width="1248" alt="2022-12-05 (19)" src="https://user-images.githubusercontent.com/114859704/205580271-140dfef7-921d-4ef7-a289-349d857d2024.png">


<br>
App home: https://homestopiaa.herokuapp.com/
   

## Getting Started
### Setup

Install gems
```
bundle install
```
Install JS packages
```
yarn install
```

### ENV Variables
Create `.env` file
```
touch .env
```
Inside `.env`, set these variables. For any APIs, see group Slack channel.
```
CLOUDINARY_URL=your_own_cloudinary_url_key
MAPBOX_API_KEY=your_own_mapbox_api_url_key

```

### DB Setup
```
rails db:create
rails db:migrate
rails db:seed
```

### Run a server
```
rails s
```

## Built With
- [Rails 7](https://guides.rubyonrails.org/) - Backend / Front-end
- [Stimulus JS](https://stimulus.hotwired.dev/) - Front-end JS
- [Heroku](https://heroku.com/) - Deployment
- [PostgreSQL](https://www.postgresql.org/) - Database
- [Bootstrap](https://getbootstrap.com/) — Styling
- [Figma](https://www.figma.com) — Prototyping

## Acknowledgements
Inspired by my own experiences living with host families in Japan. I hope others can also enjoy the experience of living with a local family a foreign country and learning the culture first hand!

## Team Members
- [Keita Wilson](https://www.linkedin.com/in/keita-wilson-1234aa142/)
- [Yulia Naumenko](https://www.linkedin.com/in/yulia-naumenko-bba121119/)
- [Ayhem Chelly](https://github.com/41FUTURE)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT L
