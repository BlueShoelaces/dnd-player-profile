# D&D Player Profile
So far, we're hosting on Heroku as `quiet-lowlands-76445` and have provisioned a Mongo DB.

## Curl to access profile API
For example:

`curl -H "Content-Type: application/json" -d '{"name":"Nicole", "character": "Wickabree"}' http://quiet-lowlands-76445.herokuapp.com/api/profiles`

To see all profiles, navigate to `http://quiet-lowlands-76445.herokuapp.com/api/profiles`.

### Other endpoints
GET, PUT, and DELETE by id: `/api/profiles/:id`
