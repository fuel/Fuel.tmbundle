# Fuel TextMate Bundle

## Install from GitHub

1. Click the "Download" button.
2. Unzip the download
3. Rename the folder to Fuel.tmbundle
4. Double-click
5. Done

## Usage

### Tab Triggers

* **fcontroller** - Creates a new Controller class (many tab-stops)
* **ftempcontroller** - Creates a new Template\_Controller class (many tab-stops)
* **faction** - Creates a new Controller Action (many tab-stops)
* **fresp** - Inserts `$this->response`
* **frespbody** - Inserts `$this->response->body = ;` (tab-stop before ;)
* **fredirect** - Inserts `Response::redirect('/');` (tab-stop on '/')
* **fview** - Inserts `View::factory('index')` (tab-stop on 'index')
* **furic** - Inserts `Uri::current()`
* **furicr** - Inserts `Uri::create('/')` (tab-stop on '/')

## Contribute!

It is very early and not much is in there yet so help out!  Feel free to fork and send pull requests!

### Contribution Rules

Very simple:

1. All Tab Triggers must start with the letter "f"
2. Must conform to our [Coding Standards](http://fuelphp.com/docs/general/coding_standards.html)
3. Add all Tab Triggers to the list above.

Try to be as concise as possible with the tab triggers, but have them still make sense.