
[![Build Status](https://ci.jenkins.io/job/Plugins/job/visualexpert-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/visualexpert-plugin/job/master/)
[![Jenkins Plugin](https://img.shields.io/jenkins/plugin/v/visualexpert.svg)](https://plugins.jenkins.io/visualexpert)
[![GitHub release](https://img.shields.io/github/release/jenkinsci/visualexpert-plugin.svg?label=changelog)](https://github.com/jenkinsci/visualexpert-plugin/releases/latest)
[![Jenkins Plugin Installs](https://img.shields.io/jenkins/plugin/i/visualexpert.svg?color=blue)](https://plugins.jenkins.io/visualexpert)

# VisualExpert Jenkins Plugin
Visual Expert plugin enables Visual Expert project users to analyze Visual Expert projects and generate documentation for the Visual Expert projects. 
The purpose of this plugin is to enable jenkins users to automate build commands for Visual Expert project analysis and documentation generation tasks using a very easy to configure user interface.

## Getting started
Once Visual Expert plugin is installed to Jenkins server, user can find the Visual Expert in build drop down list. 
Visual Expert lists the existing projects, user has currently configured in local system, and user can select a Visual Expert project from the list 
and select the project analysis and/or generate reference/code-review documentation tasks.

After installing Visual Expert plugin, configure the Visual Expert installation path in the tools.
Dashboard -> Manage Jenkins -> Tools -> Visual Expert

After setting the Visual Expert installation path, click on Apply and then Save the configuration.

![visual expert](https://github.com/jenkinsci/visualexpert-plugin/blob/main/docs/images/tools-config.png)

Add build step for Visual Expert.
![visual expert](https://github.com/jenkinsci/visualexpert-plugin/blob/main/docs/images/builder-config.png)

<p><br></p>
Select the project from the dropdown list.
<p></p>


![required field validation](https://github.com/jenkinsci/visualexpert-plugin/blob/main/docs/images/check-validation.PNG)

<p><br></p>
Select the checkboxes based on operation you would like to perform, like project analysis, generate documentations.
<p></p>


![visual expert configuration](https://github.com/jenkinsci/visualexpert-plugin/blob/main/docs/images/set-configuration.PNG)

<p><br></p>

![visual expert build console output](https://github.com/jenkinsci/visualexpert-plugin/blob/main/docs/images/console-output.PNG)

## LICENSE

Licensed under GNU General Public License Version 2, see [LICENSE](LICENSE.md)

