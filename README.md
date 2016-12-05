[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7QWUNAA58L48E) <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="7QWUNAA58L48E">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/es_ES/i/scr/pixel.gif" width="1" height="1">
</form>

Symfony Angular TodoMVC 
========================

This project is a combination of the [Symfony REST edition](https://github.com/gimler/symfony-rest-edition) project and [AngularJS](http://angularjs.org/)+[Restangular](https://github.com/mgonto/restangular) to create an implementation
of [TodoMVC](http://todomvc.com/). The majority of the AngularJS code is adapted from the existing TodoMVC implementation with [AngularJS](http://todomvc.com/architecture-examples/angularjs/#/)

Install
----------------------------------

Follow the same instructions as found on the Github page for the [symfony-rest-edition](https://github.com/gimler/symfony-rest-edition)

Essentially:

```bash
$ composer.phar install
```

Then:

```bash
$ php app/console sp:bower:install
```

Or click this:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Usage
--------------------------------

Start a webserver for the Symfony backend

```bash
$ php app/console server:run localhost:8080
```

Navigate your browser to the TodoMVC client

```bash
http://localhost:8080/todo
```

Or browse through the Rest API

```
http://localhost:8080/app_dev.php
```

All features from the [symfony-rest-edition](https://github.com/gimler/symfony-rest-edition) should be found in this project also.

Screenshots
---------------------------------

![TodoMVC Screenshot](http://i.imgur.com/P0flyyF.png "TodoMVC")

![Symfony2 Backend Screenshot](http://i.imgur.com/gybF8IS.png "Symfony2")

![API Documentation](http://i.imgur.com/XsFnJUY.png "API Docs")
