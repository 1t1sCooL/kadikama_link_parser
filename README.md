# kadikama_link_parser
A parser for collecting links to cartoons on the site kadikama.com 

The parser goes through each page and collects unique links to cartoons.

This information will be sent to the MongoDB database and saved in a JSON file.

Then, these links will be processed by the next parser to collect specific information.

This information will be provided in the form of a public API, from which the ReactJS page will then be rendered.

There will be several scripts in the project.:

The Link Parser
The parser is based on these links
The server for creating the API
The page on React.
