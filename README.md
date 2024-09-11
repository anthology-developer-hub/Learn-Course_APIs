# Learn-Course_APIs

API collections for Learn Users - CRUD operation.

## Prerequisites
Postman - latest version

## Installation
To install Postman, follow these steps:

1. Visit the [Postman website](https://www.postman.com/downloads/).
2. Download the version suitable for your platform.
3. Run the installer.

## API Enpoints

The `Api_Export.json` file contains the following APIs:

- `POST /learn/api/public/v3/courses`: Creates a new Course.
- `GET /learn/api/public/v3/courses`: Returns a list of Courses.
- `GET /learn/api/public/v3/courses/{{courseId}}`: Returns a specific course based on the given Id of a course.
- `DELETE /learn/api/public/v3/courses/{{courseId}}`: Deletes specific Course by specifing its Id.
- `PATCH /learn/api/public/v3/courses/{{courseId}}`: Updates a specific Course by specifing its Id.

## Usage

After importing the `Api_Export.json` file into Postman, you can use the APIs by sending requests to them. Ensure to set up the environment variables correctly:

- `$DOMAIN`: Learn domain name
- `$$APP_KEY`: Your application key here
- `$APP_SECRET`: Your application secret here
- `$BEARER_TOKEN`: Obtain the Access token from the API request '/learn/api/public/v1/oauth2/token' using the above values and replace the variable
- `$ID`: Id of the course
