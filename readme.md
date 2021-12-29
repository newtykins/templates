<div align="center">
	<img src="banner.png" alt="newtykins/template">
	<h1>newtykins/templates</h1>
</div>

### What is this?

This place is a place for me to store all of my [scapr](https://github.com/newtykins/scapr) project templates.

### What is scapr?

**Scapr**  (short for **sca**ffold **pr**ojects) is a command line tool I have developed to allow for the easy generation of project boilerplates, allowing for you to choose from either the default hub (being this) or your own scapr hub!

### Well... what makes it so special?

Scapr hubs have a few distinct requisites. If you look at the tree for this repository, you will notice a few things:

- The [templates](templates) folder
- The [licenses](licenses) folder
- The [scapr.yml](scapr.yml) file

These are the key requirements for your repository. When importing a new repository as a source, scapr will check out your repository to ensure that you have in each template directory a **scapr-template.yml** file, even if there is no contents. This contains metadata to be parsed to tell scapr exactly what it should expect from your template, and whether it extends any pre-existing templates. Every other file in those directories will be cloned when you make a new template.

You may also notice some text surrounded in **{{ }}** - this signifies a placeholder. These can be found both in the licenses and templates directory. These ensure that the boilerplate you generate is more relevant to the project you are trying to work on, to save you time and some headaches. A list of all of the valid placeholders may be found in the [scapr wiki](https://github.com/scapr/scapr/wiki)
