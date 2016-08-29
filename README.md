# Using Gitlab CI/Registry for automated Docker builds

Gitlab is an modern open source repository server build around git. Besides all kind of management and bug tracking features it also has a CI and a Docker Registry built-in.

This talk will show how to create automated Docker image builds with the Gitlab CI and how to deliver them with the Gitlab Registry.

This slides have been create for a talk at the Docker Meetup Bamberg:

http://www.meetup.com/de-DE/Docker-Bamberg/events/233279717/?eventId=233279717

## Usage

First clone this repository:

```shell
$ git clone https://github.com/benningm/slides-gitlab-ci-docker-builds.git
$ cd slides-gitlab-ci-docker-builds
```

Install dependencies:

```shell
$ npm install
```

Startup the presentation live server:

```shell
$ grunt serve
```

