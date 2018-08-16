# Docker & Wordpress Demo

This is a base docker-compose setup for a relatively pleasant Wordpress
development environment (without fiddling with MAMP/WAMP/whatever else you use
to get this shambling PHP behemoth up and running).

Instructions:

1. Clone the repository (or fork it, or copy-paste -- you do you!)
2. `$ docker-compose up`
3. Wait a few minutes
4. Navigate your fine self to `http://localhost:8999` and complete Wordpress
   setup

You'll note that it will clone all of Wordpress into `site/`, which we've
conveniently git-ignored (there's no need to keep all of Wordpress in version
control). That said, you can change this by editing your `.gitignore`.

From here, you're free to hack away as you like.
