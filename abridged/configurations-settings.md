
### Tools configuration

Tools following these patterns, to specify the configuration parameters to the tools.

e.gs: 
Check in the .**vscode** **folder** if you want to share settings, task configuration and debug configuration with the team. I think generally, it makes sense to share settings (e.g. whitespace vs tabs) with the team if you want to enforce settings in a team. We in the VS Code team share debug and task specific settings as well because we want our team to have the same set of debug targets and task targets for VS Code.

Setting up CircleCI for continuous integration
Create the following files in the project root: .circleci/config.yml
From the swift open source project code these configurations can be found.
.github/
.clang-format
.flake8
.mailmap

Similarly you will find 
.gitmodules
.travis.yml
.firebaserc
_config.yml
_config_now.yml
pubspec.yaml
package.json

So there is a pattern for these configurations. All of them start with a dot and a single file or a folder or a .yaml file.

YAML is a human-readable data-serialization language. It is commonly used for configuration files and in applications where data is being stored or transmitted. 

**YAML** FAQ recommends that you use .**yaml** in preference to .**yml**, but for historical reasons, many Windows programmers are still scared of using **extensions** with more than three characters and so opt to use .**yml** instead.

