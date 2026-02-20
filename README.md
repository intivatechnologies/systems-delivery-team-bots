# systems-delivery-team-bots

# LICENSE.md
The GNU General Public License version 3 (GPLv3) is a widely used, strong copyleft open-source license released in 2007
by the Free Software Foundation. It ensures that users have the right to study, share, modify, and run software. It
ensures users have the rights to study, share, modify, and run software, while requiring that any modified, derivative,
or redistributed versions remain open-source under the same license.

# pull request process
This project supports the education of the development of chatGPT bots used for systems development. Therefore, it uses an
industry-standard pull-request and review process highlighting changes committed under a team review setting.

# pull request philosophy
We generally don't leave pull requests open and handle the discussion / decision processing capabilities of pull requests
internally. Check out our <a href="https://github.com/intivatechnologies/systems-delivery-team-bots/pulls?q=is%3Apr+is%3Aclosed">closed
pull requests</a> [press ctrl/cmd + click to open in a new tab].

## maven usage through the command line
* Build the project: `mvn compile`
* Run tests: `mvn test`
* Create JAR: `mvn package`
* Clean build directory: `mvn clean`
* To compile and package the project into a JAR file, this runs the `clean`, `compile`, `test`, and `package` lifecycle phases.
