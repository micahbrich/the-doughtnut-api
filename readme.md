![GA](https://camo.githubusercontent.com/6ce15b81c1f06d716d753a61f5db22375fa684da/68747470733a2f2f67612d646173682e73332e616d617a6f6e6177732e636f6d2f70726f64756374696f6e2f6173736574732f6c6f676f2d39663838616536633963333837313639306533333238306663663535376633332e706e67)

# The Doughnuts API

For roughly as long as I've been teaching, I've been using doughnuts in every example I possibly could. They're delicious, obviously nutritious, and a great go-to.

In order to really make the most of this example, and for the secondary goal of teaching RESTful APIs & AJAX, here's a super-simple, in-memory RESTful Doughnut API.

<img width="752" src="https://cloud.githubusercontent.com/assets/25366/9149343/a5a13cbc-3d5a-11e5-8d82-fa85f5dff145.png">


It's built on the unbelievably simple & beautiful https://github.com/typicode/json-server, and there's some basic doughnut seed data.

You can:
- GET
- POST
- PUT
- PATCH
- DELETE

It's stored in memory and hosted on Heroku, which means that it'll _act_ like it persists in a response, without actually changing anything. So if you POST a new doughnut, it'll respond with details of that doughnut as if it succeeded, but if you do a GET request on the index, it won't be there. Which is actually pretty great when we've got a handful of students working off the same endpoints.

Try it! https://www.doughnuts.ga