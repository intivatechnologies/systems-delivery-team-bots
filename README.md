# systems-delivery-team-bots

# LICENSE.md
The GNU General Public License version 3 (GPLv3) is a widely used, strong copyleft open-source license released in 2007
by the Free Software Foundation. It ensures that users have the right to study, share, modify, and run software. It
ensures users have the rights to study, share, modify, and run software, while requiring that any modified, derivative,
or redistributed versions remain open-source under the same license.

# What/Who does this project exist to serve?
This project is for:
<ul>
  <li>Software development procedures</li>
  <li>Graphics designers</li>
</ul>

It is *NOT* for:
<ul>
  <li>Software engineering / MCP</li>
  <li>Images through GenAI</li
</ul>

# What problem does this project exist to solve?
Sometimes, a developer doesn't only want to do their job. They want to solve a problem for someone else. If the developer is
also a designer, they may want to use their skill as a developer to build something that will help them design an artifact of
some kind.

This project is for designers who want to produce great work under a time crunch. Usually, a designer would be much better
off with a team to complete a detailled artifact. Even better if they have good software to detail it for them. But how can
they know what kind of software they'll need before they hear the requirements of the artifact?

# What solution does this project hope to achieve?
Bringing back the waterfall model, because it's more **fun** than agile.

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
