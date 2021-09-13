# DBMS PROJECT
<!-- [![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)  --> 
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/avi-dak-hyd/django_project">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

We created this as our Database Management Lab Course Project. This is a project intended to be used by users for hosting events in a particular venue and other users can book tickets for the events. MySQL RDBMS is used to store data behind. 

Database Schema Diagram
[![Product Data Base Schema][product-database-schema]](https://example.com)

A brief description of the project is as follows
* Developed a web-based application using Django framework to provide the user with the facility of creating and booking events.
* Designed an Entity Relation Diagram and reduced this to its Database Schema Diagram using proper rules.
* Designed Graphical User Interface for SignUp, SignIn, Homepage, Search Event, Add Event, View Event, Add and Modify Review, Update Profile, View and Modify Cart   Information and Add Amount from Dummy Bank Account.
* Created MySQL Database and tables to store user information, event details, tags related to event, booking information, venue details, discount offers,           Transaction details.
* Implemented search bar in home page and results are displayed on the basis of tags, description and name.
* Implemented Similar Event block in Event Details page by searching all events with similar tags matched with displayed events.

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With
The major Frameworks and Tech Stacks used in building this project is follows
* [Bootstrap](https://getbootstrap.com)
* [Django](https://www.djangoproject.com/)
* [Tailwind CSS](https://tailwindcss.com/)
* [MySQL](https://www.mysql.com/)
* [Python](https://www.python.org/)
* [HTML5]()
* [CSS3]()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites
This project assumes you have virtualenv installed. In case not installed install python virtual env to manage dependencies* virtualenv
  ```sh
  pip install virtualenv
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/avi-dak-hyd/dbms_project-EMS
   ```
2. Go to the directory where it is cloned and then open the terminal and run as follows.
   ```sh
   cd django_project-EMS/EMS
   ```
3. Activate `venv` virtual-env
   ```sh
   source venv/bin/activate
   ```
4. Execute the following command to run the server:
    ```bash
    python3.8 manage.py runserver 8181
    ```
5. Open the following address in your browser
    ```bash
    http://127.0.0.1:8181/home
    ```



## Roadmap

See the [open issues](https://github.com/avi-dak-hyd/dbms_project/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact
LinkedIn & Email - [Avijit Mandal](https://www.linkedin.com/in/avijit-mandal-17b446163/) - avijitmandal2001@gmail.com

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Pillow](https://pypi.org/project/Pillow/2.2.2/)
* [mysqlclient](https://pypi.org/project/mysqlclient/)
* [Tailblocks](https://tailblocks.cc/)
* [MySql Workbench](https://www.mysql.com/products/workbench/)
* [Pycharm IDE](https://www.jetbrains.com/pycharm/)
* [Django Documentation](https://docs.djangoproject.com/en/3.2/)
* [MySQL Documentation](https://dev.mysql.com/doc/)
* [Database System Concepts 6th edition.pdf](https://www.db-book.com/db6/index.html)
* [ERDPlus](https://erdplus.com/)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: images/event_details_ii.png
[product-database-schema]: images/database_schema.jpeg


