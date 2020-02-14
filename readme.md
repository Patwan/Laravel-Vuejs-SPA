# Laravel-and-vuejs-spa
A simple project illustrating creation of a SPA using Vuejs on the frontend and Laravel 
framework on the backend. The application has authentication functionality whereby a user
can register and login and perform CRUD funcionality on existing users. Data from the backend
is exposed via a RESTFUL API.

# Technologies used
* AdminLTE template for the dashboard <br/>
* Laravel PHP framework <br/>
* Vuejs JavaScript feamework <br/>
* MySQL RDBMS <br/>

# Installation
* Clone the project.  **git clone project-name**  <br/>
* Run **composer install** <br/>
* Copy .env.example to .env **cp .env.example .en** and configure database credentials <br/>
* Run **php artisan migrate** for the migrations <br/>
* Run **php artisan key:generate** <br/>
* Run **npm install** for running Vuejs depedencies found in package.json file <br/>
* Run **npm run serve** to start the Vuejs server
* Run **npm run dev** for Laravel mix to compile frontend assets

## License
This program is free software published under the terms of the GNU [Lesser General Public License](http://www.gnu.org/copyleft/lesser.html). <br/>
You can freely use it for commercial and non-commercial projects.


