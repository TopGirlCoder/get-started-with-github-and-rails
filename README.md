<h1>tgc-website</h1>
<p>Framework: Ruby on Rails</p>
<p>Languages: Ruby, JavaScript, HTML, CSS</p>
<p>Database: PostgreSQL</p>
<h3>To dos</h3>
<ol>
	<li><del>Create a new repository on GitHub:</del></li>
	<ol>
		<li><del>Go into your GitHub profile, click 'Repositories'.</del></li>
		<li><del>Click the green button on the right 'New'.</del></li>
		<li><del>Under 'Repository Name', give your new repository a name.</del></li>
		<li><del>Under 'Description', describe your new repository.</del></li>
		<li><del>Do not initialize with a 'README' and '.gitignore'. Rails will provide these files.</del></li>
	</ol>
	<li><del>Create a new Rails application at the command line:</del></li>
	<ol>
		<li><del>Go into your terminal (shell) on your system.</del></li>
		<li><del>Navigate to the directory that will eventually contain your Rails app. Use 'cd' to get there, i.e. $ cd desktop/projects. If you need to create a new directory called projects, use at the command line $ mkdir projects.</del></li>
		<li><del>Type into the terminal:</del></li>
			<ol>
				<li><del>$ rails new <project name> --database=postgresql</del></li>
				<li><del>$ bundle install</del></li>
				<li><del>git init</del></li>
				<li><del>git add .</del></li>
				<li><del>git commit -m ‘Initial commit’</del></li>
				<li><del>git status</del></li>
				<li><del>git remote add origin https://github.com/[username]/[repository].git</del></li>
				<li><del>git push -u origin master</del></li>
			</ol>	
		<li><del>Open a new tab in the terminal, and run $ rails server. Now you can see the project at http://localhost:3000. (When ready to quit the server, use control-c.)</del></li>	
	</ol>	
	<li>Develop a Rails login and authentication system for users</li>
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