# kadikama_link_parser
<h1>A parser for collecting links to cartoons on the site kadikama.com</h1> 

<p>The parser goes through each page and collects unique links to cartoons.</p>

<p>This information will be sent to the MongoDB database and saved in a JSON file.</p>

<p>Then, these links will be processed by the next parser to collect specific information.</p>

<p>This information will be provided in the form of a public API, from which the ReactJS page will then be rendered.</p>

<h3>There will be several scripts in the project.:</h3>
<ul>
  <li>The Link Parser</li>
  <li>The parser is based on these links</li>
  <li>The server for creating the API</li>
  <li>The page on React.</li>
</ul>

