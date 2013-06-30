# SandCastle - Events
SandCastle is a collection of tools for creating a community website/portal. It is currently under heavy development, kickstarted by the [mozilla.org.uk][1] website revamp in 2012. Built ontop of the [CodeIgniter][2] for ease of use, however each componenet should provide a good starting point for those wishing to use another framework (or even pure PHP).

This [Spark][3] is the beginings of an event listing system. It provides the needed functions to make storing and listing upcoming events easy as 3.141526... More specifically it deals with the database side of things.

When talking about the "database result object" this refers to the CodeIgniter database result object, i.e. `$query->result()`

I'm going to assume that you're using [CodeIgniter][2], and thus you have a basic understanding of PHP. These are both prerequisites if you want to follow the instructions from now on.

## Installation
First you will need to install the [Spark Package Manager][4]. Once you have move into the root of your CodeIgniter application and issue the following command:

	php tools/spark install sandcastle-events 

To load the model into your application use the following, replacing `x.x.x` with a version number (see [tags][5]).

	$this->load->spark('sandcastle-events/x.x.x');

The main model will now be available using:

	$this->event_model

## Usage

> More details to come... till then take a nose at [the source][6]

## License
### CodeIgniter
For more information on the CodeIgniter License read it over at [http://ellislab.com/codeigniter/user-guide/license.html][7].

### SandCastle
This Source Code Form is subject to the terms of the Mozilla Public
License, v. 2.0. If a copy of the MPL was not distributed with this file,
You can obtain one at [mozilla.org/MPL/2.0][8].

[1]: http://www.mozilla.org.uk/
[2]: http://ellislab.com/codeigniter/
[3]: http://getsparks.org/
[4]: http://getsparks.org/install/
[5]: https://github.com/fuzzyfox/sandcastle-planet/tags
[6]: ./models/event_model.php
[7]: http://ellislab.com/codeigniter/user-guide/license.html
[8]: http://mozilla.org/MPL/2.0/
