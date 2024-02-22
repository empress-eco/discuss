<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="discuss logo" height="50" />
  <h1 align="center">Discuss: Enhancing Remote Work Communication</h1>
  <p align="center">
    An open-source tool designed for structured and efficient asynchronous discussions in remote teams.
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/discuss/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/discuss/issues">Request Feature</a>
  </p>
</div>

## About The Project

Discuss is a pioneering communication tool specifically designed for remote teams. It streamlines structured, asynchronous discussions, ensuring your team can effectively keep track of multiple conversations and organize discussions around projects and teams. With Discuss, your team's knowledge archive is always at your fingertips, fostering collaboration and efficiency.

### Key Features
- Organize discussions into projects and teams.
- Surface important information for your project and team in the Readme.
- Simple layout that optimizes readability of discussions.
- Customize your Team and Project with emojis.
- People directory with each person's profile page.
- Set cover image, profile photo, short bio, and an "About me" section.
- Powerful search capabilities to find older discussions.
- A common discussions feed that shows discussions from across projects and teams.

### Technical Stack
Discuss is built on the Framework, a Python web-framework. Here are some of the major tools used in the project:
- [Python](https://www.python.org)
- [Redis](https://redis.io/)
- [MariaDB](https://mariadb.org/)
- [Socket.io](https://socket.io/)
- [VueJS](https://vuejs.org)
- [TailwindCSS](https://tailwindcss.com)

## Setup Instructions

### Prerequisites
You need Docker, docker-compose, and git setup on your machine. If you haven't installed these yet, follow the [Docker documentation](https://docs.docker.com/) for guidance.

### Installation
1. Clone the project repository using the link below:
```sh
git clone https://github.com/empress-eco/discuss.git
```
2. Navigate into the Docker directory and run the Docker compose file:
```sh
cd discuss/docker
docker-compose up
```
3. Wait for the setup script to create a site. You can then access `http://localhost:8000` in your browser. Use the following credentials to log in:
   - Username: `alex@example.com`
   - Password: `123`

## Contributing
We warmly welcome contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is under the MIT License. Your contributions are also licensed under the MIT License.

## Acknowledgements
A special thank you to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.