<h1>How to make a new Github repository for new Rails project</h1>
<p>Framework: Ruby on Rails</p>
<p>Languages: Ruby, JavaScript, HTML, CSS</p>
<p>Database: PostgreSQL</p>

<h3>Contents</h3>
<ol>
	<li><a href="#gettingstarted">Getting started: GitHub and Rails</a>
	<li><a href="#userauthentication">Users: Develop a Rails login and authentication system for users</a></li>
</ol>

<ol>
	<h3><li><a name="gettingstarted">Getting started: GitHub and Rails</a></li></h3>
	<ol>
		<li>Create a new repository on GitHub</li>
		<ol>
			<li>Go into your GitHub profile, click 'Repositories'.</li>
			<li>Click the green button on the right 'New'.</li>
			<li>Under 'Repository Name', give your new repository a name.</li>
			<li>Under 'Description', describe your new repository.</li>
			<li>Do not initialize with a 'README' and '.gitignore'. Rails will provide these files.</li>
		</ol>
		<li>Create a new Rails application at the command line</li>
		<ol>
			<li>Go into your terminal (shell) on your system.</li>
			<li>Navigate to the directory that will eventually contain your Rails app. Use 'cd' to get there, i.e. $ cd desktop/projects. If you need to create a new directory called projects, use at the command line $ mkdir projects.</li>
			<li>Type into the terminal:</li>
				<ol>
					<li>$ rails new <project name> --database=postgresql</li>
					<li>$ bundle install</li>
					<li>git init</li>
					<li>git add .</li>
					<li>git commit -m ‘Initial commit’</li>
					<li>git status</li>
					<li>git remote add origin https://github.com/[username]/[repository].git </li>
					<li>git push -u origin master</li>
				</ol>	
			<li>Open a new tab in the terminal, and run $ rails server. Now you can see the project at http://localhost:3000. When you're ready to quit, use control-c to quit the server.</li> 
			<ol>
				<li>If the terminal gets closed inadvertently before quiting the server, you'll need to open a new terminal window and hunt down the process that is still running by typing into the command line: $ ps aux | grep rails. This will give you some PID number (like 45345) that you will then type into the command line: $ kill -9 [PIDnumber].</li> 
				<li>Alternatively, find the number by typing into the command line: $ lsof -wni tcp:3000. The port is typically 3000, but you'll want to change this if it is some other localhost. See the PID number in the PID column, then type into the command line: $ kill -9 [PIDnumber].</li>
			</ol>	
		</ol>
	</ol>	
	<h3><li><a name="userauthentication">Users: Develop a Rails login and authentication system for users</a></li></h3>
	<ol>
		<li>Create a data model for users of the site.</li>
		<li>Find a way to store the users data.</li>
		<li>Give users the ability to sign up for our site.</li>
		<li>Activate users account and confirm valid email address and password resets.</li>
		<ol>
			<li>Validate: Email addresses should be unique, passwords should be at least 6 characters.</li>
		</ol>
		<li>Give users a way to create a profile page.</li>
		<li>Give users that have signed up a way to log in and log out.</li>
		<li>Protect user pages from improper access.</li>
		<li>Test-driven development for model validations.</li>
		<ol>
			<li>Test for valid and invalid cases.</li>
		</ol>	
	</ol>
</ol>	
