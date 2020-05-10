# Yet Another Social network
 A simple social media application with users, posts, likes and comments - developed using React, Node, Express and MongoDB.

## CONNECT
 A YASN exclusively for students of DAIICT! 
 
 ![Screenshots](https://res.cloudinary.com/hitgo/image/upload/v1589019590/Screenshot_2020-05-09_at_3.43.24_PM-min_jbw0af.png)![Screenshots](https://res.cloudinary.com/hitgo/image/upload/w_430,h_600,c_scale/v1589095090/IMG_4531-min_exllv9.jpg)         ![Screenshots](https://res.cloudinary.com/hitgo/image/upload/w_430,h_600,c_scale/v1589095090/IMG_4528-min_z7jkit.jpg)![Screenshots](https://res.cloudinary.com/hitgo/image/upload/w_430,h_600,c_scale/v1589095090/IMG_4530-min_mqb8kf.jpg)  ![Screenshots](https://res.cloudinary.com/hitgo/image/upload/w_430,h_600,c_scale/v1589095090/IMG_4529-min_r5kuim.jpg)


## Development

- You need Node & Yarn to start the development environment. Download them here - [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com).

- Optionally you can setup a `.env` file in the root of the repository to set the server url (if you don't do this it will default to `http://localhost:4848`). The file should look like this:

```bash
REACT_APP_SERVER_URL=#Darkrai server url
REACT_APP_CONNECT_SERVER_URL=#Connect server url 
REACT_APP_GOOGLE_CLIENT_ID=#Google auth client ID
REACT_APP_CLOUDINARY_CLOUDNAME=#Cloudinary cloud name
REACT_APP_UPLOAD_PRESET=#Cloudinary Upload Preset
```

- Run the development server using:

```bash
yarn start
```

- Build the production level extension:

```bash
yarn build
