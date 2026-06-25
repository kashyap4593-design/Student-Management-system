# Django Student Management System 👨‍🎓

A modern Student Management System 👨‍🎓 with features like Interactive Dashboard 🤩 Attendance Management 🏫Provide Feedback ✍ Result Generation 📜 Leave Application 🍂

![SMS_Banner](https://github.com/Akash1362000/akash1362000.github.io/blob/master/styles/images/Django%20Student%20Management%20System%20Banner.jpg)

[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://student-management-webapp.herokuapp.com/)
[![travis-ci](https://api.travis-ci.com/Akash1362000/Django_Student_Management_System.svg?token=nv6BYq1BY3w4kf8uZuGj&branch=main)](https://travis-ci.com/github/Akash1362000/Django_Student_Management_System/)
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FAkash1362000%2FDjango_Student_Management_System%2F&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/Akash1362000/Django_Student_Management_System/graphs/commit-activity)


Checkout the live Website [here](https://student-management-system-4jym.onrender.com/)!





## Development 👨‍💻
Note : Make sure you have Python version 3.8+

Environment Setup 🚀

`$ git clone https://github.com/Akash1362000/Django_Student_Management_System.git`

`$ cd Django_Student_Management_System/`

Create `.env` file (refer `.env.example` file)

Generate `SECRET_KEY` from [here](https://djecrety.ir/)

Generate your `CAPTCHA_SECRET` from [here](http://www.google.com/recaptcha/admin)

Copy your `SITE KEY` after generating `CAPTCHA_SECRET` and paste it in `data-sitekey` in `student_management_app/templates/login_page.html` (replace the current key with your key)

## Database Setup

Install Postgres Latest version from [here](https://www.postgresql.org/download/)

Install pgAdmin from [here](https://www.pgadmin.org/download/)

Create a Database using pgAdmin by following the steps mentioned [here](https://www.tutorialsteacher.com/postgresql/create-database)

Update your `DATABASE_URL` in `.env` with your DB details like `USER`, `PASSWORD` and `DB_NAME`

---

If virtualenv is not installed [(What is virtualenv?)](https://www.youtube.com/watch?v=N5vscPTWKOk&t=313s):

`$ pip install virtualenv`

Create a virtual environment

`$ virtualenv venv`

Activate the environment everytime you open the project

`$ source venv/Scripts/activate`

Install requirements 🛠

`$ pip install -r requirements.txt`

`$ pre-commit install`

Run migrations for Database

`$ python manage.py migrate`

Create superuser for Admin Login 🔐

`$ python manage.py createsuperuser`

Enter your desired username, email and password. Make sure you remember them as you'll need them in future.

eg.

    Username: admin

    Email: admin@admin.com

    Password: HighlyConfidentialPassword

All Set! 🤩

Now you can run the server to see your application up & running 🚀

`$ python manage.py runserver`

To exit the environment ❎

`$ deactivate`

Every time you want to open the application in browser, make sure you run:

`$ source venv/Scripts/activate`

`$ python manage.py runserver`

---
## Docker Setup (Optional) ![](https://skillicons.dev/icons?i=docker)

If you want to use Docker to run this project, you need to do the following steps:
- Install Docker for your OS from [here](https://www.docker.com/products/docker-desktop/)
- Run `docker --version` and `docker compose --version` [In Windows, you need to run `docker-compose --version` to check the version]
- If you see both the versions, then Docker is successfully installed on your system and you can follow along
- If you don't see the version, check with your Docker installation
- Open `docker-compose.yml` file and update the value of `CAPTCHA_SECRET` with your generated key. You can generate it from [here](http://www.google.com/recaptcha/admin) 
- Run `docker compose up -d`
- Run `docker exec -it student_management_system sh -c "python manage.py createsuperuser"` to create a new superuser
- Access the app at [http://localhost:8000](http://localhost:8000)
- To stop the container, run `docker compose stop` from the project root
- To restart the container, run `docker compose start` from the project root
- To delete the container, run `docker compose down` from the project root

---

## A Glimpse of the Dashboard 😍

![Dashboard](https://i.imgur.com/vN530l3.png)

## Stargazers

[![Stargazers[( ](https://github.com/kashyap4593-design/Student-Management-system)](https://github.com/kashyap4593-design/Student-Management-system))

Liked our work? 🤔 Do star(https://github.com/kashyap4593-design/Student-Management-system)) repository ⭐ It'll motivate us more 😁

ES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
