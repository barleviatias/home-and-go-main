
<body>
    <h1>Airbnb Clone Full Stack Project</h1>
<h2>Overview</h2>

<p>This is a full-stack web application that replicates the core functionalities of Airbnb. The project uses React for the front-end, Node.js for the back-end, Redux for state management, and SASS for styling.</p>

<h2>Table of Contents</h2>

<ul>
    <li><a href="#demo">Demo</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#tech-stack">Tech Stack</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="demo">Demo</h2>

<p>You can access the live demo of this project <a href="#">here</a>.</p>

<h2 id="features">Features</h2>

<ul>
    <li>User authentication (sign up, log in, log out)</li>
    <li>Property listings</li>
    <li>Property search</li>
    <li>Booking system</li>
    <li>User profiles</li>
    <li>Reviews and ratings</li>
</ul>

<h2 id="tech-stack">Tech Stack</h2>

<ul>
    <li>Front-end: React, Redux, SASS</li>
    <li>Back-end: Node.js, Express</li>
    <li>Database: MongoDB</li>
    <li>Authentication: JWT (JSON Web Tokens)</li>
</ul>

<h2 id="getting-started">Getting Started</h2>

<p>To get a local copy up and running, follow these steps.</p>

<h3>Prerequisites</h3>

<p>Make sure you have the following installed on your machine:</p>

<ul>
    <li>Node.js</li>
    <li>npm (Node Package Manager)</li>
    <li>MongoDB</li>
</ul>

<h3 id="installation">Installation</h3>

<ol>
    <li><strong>Clone the repository:</strong></li>
    <code>git clone https://github.com/your-username/airbnb-clone.git</code>
    <li><strong>Install dependencies for both client and server:</strong></li>
    <code>
        <ul>
            <li>cd client</li>
            <li>npm install</li>
            <li>cd ../server</li>
            <li>npm install</li>
        </ul>
    </code>
    <li><strong>Set up environment variables:</strong></li>
    <p>Create a <code>.env</code> file in the <code>server</code> directory and add the following:</p>
    <code>MONGO_URI=your_mongodb_connection_string<br>JWT_SECRET=your_jwt_secret</code>
    <li><strong>Start the application:</strong></li>
    <code>
        <ul>
            <li>cd server</li>
            <li>npm run dev</li>
            <li>cd ../client</li>
            <li>npm start</li>
        </ul>
    </code>
    <li>The client will be running on <code>http://localhost:3000</code> and the server on <code>http://localhost:5000</code>.</li>
</ol>

<h2 id="usage">Usage</h2>

<p>Once the application is running, you can navigate to <code>http://localhost:3000</code> in your browser to start using the application.</p>

</body>
