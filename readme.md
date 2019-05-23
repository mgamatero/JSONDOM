1. create a valid JSON structure that will represent the following
		* object structure:
		*
		* An object called people is a collection of person objects.  Each person object
		* has the following attributes: name, age, occupation, and hobbies,
		* where hobbies is collection of activity values. (Please use the data
		* from step 2 for the values of your JSON fields)
		*
		* 2. after you have created the JSON structure, you will need to create
		* the necessary JavaScript code to traverse your JSON object and create the
		* following HTML structure:
		*
		* NOTE: this structure must be data driven, meaning that the field names such
		* as name, age, etc. cannot be hardcoded.  Also, the number of tabs cannot be
		* hardcoded, it must be driven by the number of people present in the JSON.
		*
			<h1>People</h1>
			<div class="tab closed">
				<h3>Edward's Info</h3>
				<div class="person">
					<span>name: Edward</span>
					<span>age: 76</span>
					<span>occupation: UI Developer</span>
					<span>hobbies:</span>
					<ul>
						<li>Bowling</li>
						<li>Tennis</li>
					</ul>
				</div>
			</div>
			<div class="tab even closed">
				<h3>Jorge's Info</h3>
				<div class="person even">
					<span>name: Jorge</span>
					<span>age: 25</span>
					<span>occupation: Designer</span>
					<span>hobbies:</span>
					<ul>
						<li>Soccer</li>
						<li>Food Tasting</li>
					</ul>
				</div>
			</div>
			<div class="tab closed">
				<h3>Naveen's Info</h3>
				<div class="person">
					<span>name: Naveen</span>
					<span>age: 23</span>
					<span>occupation: Programmer</span>
					<span>hobbies:</span>
					<ul>
						<li>Video Games</li>
					</ul>
				</div>
			</div>
		*
		* 3. Once your code has created the HTML structure and appended it to the body,
		* add a click event listener to the h3 tag that will do the following:
		*
		* When the user clicks on it, the parent div will toggle between the 'closed' and
		* 'opened' class.  Thus, the person's info will be either displayed or hidden
		* depending on the active class.
		**/
