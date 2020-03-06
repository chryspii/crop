:warning: This project is currently **under development**! however ready to use.

:warning: Dataset and weight are not provided!

:warning: Darknet Built under Windows with GPU!

# Crop Area Condition Detection App
A web-based application for detecting crop area condition using YOLOv3

## Tools
* [NodeJS](https://nodejs.org/)
* [ExpressJS](https://expressjs.com/)
* [Python 3.x](https://www.python.org/)
* [Darknet](https://github.com/AlexeyAB/darknet)
* [YOLOv3](https://pjreddie.com/darknet/yolo/)
* [MongoDB](https://www.mongodb.com/)
* [Bootstrap](https://getbootstrap.com/)

## How to deploy
1. Clone the git repository
    ```bash
    git clone https://github.com/chryspii/crop.git
    ```

2. Install all required dependencies
    ```bash
    npm install
    ```

3. Run the application using **Nodemon** 
    ```bash
    nodemon start
    ```

## Documentation
### Directory Structure
```bash
./crop/
└── bin/                    # config port and host
│   └── www
└── public/                 # website assets
│   └── css/
│   └── img/
│   └── js/
│   └── scss/
│   └── vendor/
└── routes/                 # controller
│   └── css/
│   └── img/
└── views/                  # front-end 
│   ├── error.pug
│   ├── index.pug
│   └── layout.pug
│   └── login.pug
│   └── presenter.pug
│   └── presenter-result.pug
│   └── questioner.pug
│   └── questioner-result.pug
└── app.js                  # main file
└── package.json            # dependencies
