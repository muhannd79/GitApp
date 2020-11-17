### Shows API Requests
---

The show API is an authenticated API endpoint allowing authorize user to get a list of shows information.

### Request

Url - /shows The request object should contain the Bearer authorization in the header.


### Success Response
  
  
  
  

### Filter

We can filter result by genre or language

### Example

Search shows by language

- Url - /shows ?language=English

Search shows by genre

- Url - /shows ?genre=Drama

### Sort

Sort according to a specific field.

### Example

Sort shows by title.

- ASC: GET /shows?\_sort=title:ASC
- DESC: GET /shows?\_sort=title:DESC

### Sorting on multiple fields

- GET /shows?\_sort=title:asc,released\_on:desc
- GET /shows?\_sort=title:DESC,released\_on:ASC

### Error Response
