<p align="center"></p>
Materio - Vuetify VueJS Laravel Free Admin Template
</p>


## Introduction

If you’re a developer looking for an admin dashboard that is developer-friendly, rich with features, and highly customizable look no further than Materio. We’ve followed the highest industry standards to bring you the very best admin template that is not only fast and easy to use but highly scalable. Offering ultimate convenience and flexibility, you’ll be able to build whatever application you want with very little hassle.

Build premium quality applications with ease. Use our innovative admin template to create eye-catching, high-quality, and high-performing single-page applications. Your apps will be completely responsive, ensuring they’ll look stunning and function flawlessly on desktops, tablets, and mobile devices.

## Installation ⚒️

> We recommend you use yarn

1. Install composer packages

   ```bash
   composer install

   ```

2. In the root directory, you will find a file named .env.example, rename the given file name to .env and run the following command to generate the key (You can also setup your database credentials here).

   ```bash
   php artisan key:generate

   ```

3. By running the following command, you will be able to get all the dependencies in your node_modules folder:

   ```bash
   yarn

    # npm install [for npm]
   ```

4. To run the project, you need to run following command in the project directory. It will compile the php files & all the other project files. If you are making any changes in any of the php file then you need to run the given command again.

   ```bash
   yarn dev

    # npm run development [for npm]
   ```

5. To serve the application you need to run the following command in the project directory. (This will give you an address with port number 8000.)

   ```bash
   php artisan serve

   ```

6. To change the port address, run the following command:

   ```bash
    php artisan serve --port=8080 // For port 8080
    sudo php artisan serve --port=80 // If you want to run it on port 80, you probably need to sudo.

   ```

7. `Watching for changes`: If you want to watch all the changes you make in the application then run the following command in the root directory.

   ```bash
    yarn watch
    
    # npm run watch [for npm]
   ```

8. `Building for Production:` If you want to run the project and make the build in the production mode then run the following command in the root directory, otherwise the project will continue to run in the development mode.

**Make sure to change the APP_ENV=local variable's value APP_ENV=production.**

   ```bash
    yarn prod
    
    # npm run production [for npm]
   ```

## Required Permissions

If you are facing any issues regarding the permissions, then you need to run the following command in your project directory:

  ```
  sudo chmod -R o+rw bootstrap/cache
  sudo chmod -R o+rw storage
  ```

## What's Included 📦

- Dashboard
- Account Settings
- Pages
  - Login
  - Register
  - Error
- User Interface
  - Typography
  - Icons
  - Basic Cards
  - Tables
  - Form Layouts
