# systems-delivery-team-bots

# About
AI systems for delivering my systems to get more done for a user who has assigned me a deadline

# LICENSE.md
The GNU General Public License version 3 (GPLv3) is a widely used, strong copyleft open-source license released in 2007 by the Free Software Foundation. It ensures users have the rights to study, share, modify, and run software, while requiring that any modified, derivative, or redistributed versions remain open-source under the same license.

# What/Who does this project exist to serve?
This project is for:
<ul>
  <li>Software development procedures</li>
  <li>Graphics designers</li>
</ul>

It is *NOT* for:
<ul>
  <li>Software engineering / MCP</li>
  <li>Generating images through GenAI</li
</ul><br >

# What problem does this project exist to solve?
Sometimes, a developer doesn't only want to do their job. They want to solve a problem for someone else. If the developer is also a designer, they may want to use their skill as a developer to build something that will help them design an artifact of some kind. This type of work usually requires putting in an extra milestone, and an extra milestone usually involves the pressure of a deadline.

# What solution does this project hope to achieve?
Reactivating the waterfall model, simply because it’s more fun than agile.

# What problem is faced in completing this project?
<ul>
  <li>I don’t yet fully understand the requirements of the project or what makes the bots unique</li>
  <li>I can’t afford paying for any alternative/competitor subscription.</li>
</ul>

# What solution is required to alleviate this project or competing subscriptions if necessary?
Something that gives ChatGPT real-time access to my code repo as I have it act on behalf of the bots. Refer to
<a href="https://github.com/intivatechnologies/repo-context-for-ai">repo-context-for-ai</a> for the solution that can alleviate the requirements of this project.

# What are the roles of the bots involved?
<i>A quick note on what the bots aren&#39;t</i><br >
The bots are not to be enrolled in MCP tasks. But that doesn’t mean that they can’t be used to create systems that can be used by MCP systems.

*Role of each non-supervisor*
<ul>
  <li>Tester that writes tests for continuation of test-driven-development by the coder</li>
  <li>Debugger that follows debugging procedures and communicates bugs either by messaging the tester or falling back to the coder</li>
  <li>Writer that updates a requirements doc</li>
  <li>Educator that defines concrete paths to refactoring the code and eliminating code smells</li>
  <li>Constructor that sets up the project and implements best practices for all utilities that get integrated. He’s unfamiliar with IDE’s and prefers build tools instead.</li>
  <li>Researcher that finds online tools and documentation for efficiency in completing operation</li>
</ul>

*Role of each supervisor (non-bot included)*
<ul>
  <li>Coder that behaves as a team lead to the bots and is an active human controlling the system</li>
  <li>An intercessor on behalf of the non-supervisor bots that communicates with an open channel to the coder and a closed channel to the non-supervisor bots (as in the non-supervisor bots can’t speak for themselves)</li>
  <li>Scans the open/closed channel for all conversation that led to change that the coder kept</li>
</ul>

## pull request process
This project supports the education of the development of chatGPT bots used for systems development. Therefore, it uses an
industry-standard pull-request and review process highlighting changes committed under a team review setting.

## pull request philosophy
We generally don't leave pull requests open and handle the discussion / decision processing capabilities of pull requests
internally. Check out our <a href="https://github.com/intivatechnologies/systems-delivery-team-bots/pulls?q=is%3Apr+is%3Aclosed">closed
pull requests</a> [press ctrl/cmd + click to open in a new tab].

### maven usage through the command line
* Build the project: `mvn compile`
* Run tests: `mvn test`
* Create JAR: `mvn package`
* Clean build directory: `mvn clean`
* To compile and package the project into a JAR file, this runs the `clean`, `compile`, `test`, and `package` lifecycle phases.
