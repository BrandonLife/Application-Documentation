<h1>Game Mods</h1>
<hr>
<p>A library of mods for video games</p>

<h1>Description</h1>
<p>This application allows video game players to choose from a variety of mods to use in any video game</p>

<h1>Demo</h1>
<p>You can find a link to this application at <a src="#">vidgmods.com</a></p>


<h1>Technologies</h1>
<ul>
<li>MongoDB</li>
<li>ExpressJs</li>
<li>ReactJs</li>
<li>NodeJs</li>
</ul>

<h1>How to set up</h1>
<h2>Front end</h2>
<ol>
<li>Cd into your front end directory</li>
<li>npm install boostrap, and react-bootstrap</li>
<li>After that type create-react-app nameofproject</li>
<li>Cd into create-react-app directory</li>
<li>In the command line, type npm start</li>
</ol>
<h2>Back end</h2>
<ol>
<li>Cd into your back end directory</li>
<li>npm install mongoose and express</li>
<li>After those are installed go to package.json</li>
<li>In the package.json, go to scripts and type "dev": "npx nodemon" </li>
<li>In the command line, type npm run dev</li>
</ol>
<h2>Coding standards</h2>
<p>It is best to use dry code and prettier for formatting</p>

<h1>Issues</h1>
<p>Users have reported issues with some mods. This has to do with the versioning of the app. A new version is being worked on.</p>

<h1>For Api usage, use these endpoints</h1>
<h2>All endpoints use the base url /vidgmods</h2>
<table>
<tr>
<th>Route</th>
<th>Endpoint</th>
<th>Summary</th>
</tr>

<tr>
<td>Home</td>
<td>/</td>
<td>The home route for all things vidgmods; all mods, versions, pics, gifs, packages, req objects, all games</td>
</tr>

<tr>
<td>About</td>
<td>/about</td>
<td>The about route for more info on vidgmods application</td>
</tr>

<tr>
<td>Specific game or mod</td>
<td>/:id</td>
<td>The specific route for specific games or mods</td>
</tr>

<tr>
<td>Delete</td>
<td>/:id</td>
<td>The delete route for specific games or mods</td>
</tr>

<tr>
<td>Update</td>
<td>/:id</td>
<td>The update route for specific games or mods</td>
</tr>

<tr>
<td>Post</td>
<td>/</td>
<td>The post route to create new mods or games </td>
</tr>

</table>
