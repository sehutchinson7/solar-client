<h1><b>Boston Solar Mapping App</b></h1>
<p> This is the client-side repository for the Boston Solar Mapping app.
<p>Check out the deplyed site: https://hutchinsonGIS.com/solar-client
</p>
</p>
<h3> Background: </h3>
  <p>The goal for the project is to explore solar potential for the Greater Boston Area.
  <img src="Homepage_Screenshot.png" alt="Homepage">
<h3> Technologies Used: </h3>
<ul>
  <li>Atom Editor</li>
  <li>CSS</li>
  <li>Google Maps API for Javascript</li>
  <li>Google Places API</li>
  <li>Grunt/npm</li>
  <li>HTML</li>
  <li>Javascript</li>
</ul>
<h3> Project Description & Planning Process </h3>
<p>
</p>
<h5> Wireframes & User Stories</h5>
<p> The developer utilized white boarding and wireframes for organization and planning purposes:
<ul>
  <li><a href="https://imgur.com/1wFsMGF">View Wireframe </a></li>
  <li><a href="https://imgur.com/AynBARd">Planning</a></li>
</ul>
<h5>User Stories</h5>
<ul>
  <li>As a user, I want to search my address on a web map.</li>
  <li>As a user, I want to view my address using satellite imagery as the basemap.</li>
  <li>As a user, I want to draw a solar installation polygon over an area.</li>
  <li>As a user, I want to calculate the nominal power for the drawn installation.</li>
</ul>
<h5>Developer Stories</h5>
<ul>
  <li>As a developer, I want to utilize the Google Maps Javascript API for the webmap,
  and display satellite imagery by default.</li>
  <li>As a developer, I want to use the Places API library to autocomplete places and addresses when a user begins typing into the search box.</li>
  <li>As a developer I want to utilize the draw capabilities within the Google API to allow a user to draw a rectangle or customized polygon shape on the map.</li>
  <li>As a developer, I want to calculate solar pv based on the specified polygon dimensions.</li>
  <li>As a developer, I want to incorporate data that is relevant to assessing solar potential. For example, lidar, elevation, Digital Elevation Models (DEM), canopy cover, etc. </li>
  <li>As a developer, I want to create an intuitive, user-frienly UI experience for the user.</li>
</ul>
<h3>Instructions</h3>
<p>To view this project in more detail please follow these steps:
<ol>
  <li>Fork and clone this repository.</li>
  <li>Change into the new directory.</li>
  <li>Install dependencies by running <code>npm install</code> within the repository.</li>
  <li>In a separate terminal window, run <code>grunt serve</code> from within the same repository.</li>
  <li>Navigate to local host on your browser to view webpage.</li>
</ol>
<h3> Next Steps: </h3>
<p>The next steps in project development will focus on gathering the appropriate data to assess and calculate nominal power of the drawn installation. A potential stepping stone to building a solar calculator would be to first calculate surface area of the drawn polygon using the geometry feature in Google Maps API for Javascript. </p>

<p>Next steps will also focus on researching and gathering the appropriate datasets. Potential Data sources for the project might include lidar data, elevation/Digital Elevation Models (DEM), etc. It would also be beneficial to include a shapefile (geojson) of existing solar panel installations in the area.</p>

<p>Solar panel data for 2014 was downloaded from the City of Cambridge, imported into QGIS and converted to geojson. The goal is to overlay this data with the webmap so that a user can view solar panel installations within their neighborhood or area of interest. Ideally, the project would incorporate more recent solar installation data. This feature has not yet been deployed.</p>

<p>Future development will work on creating a better UI experience for the user.</p>

For inquires, contact: sara@hutchinsonGIS.com
</ul>
