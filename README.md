# ood-new-app
How-to guide to creating new OOD apps

## Documents to be created

* Guide: Set up your development environment
* Guide: Choose a scientific application and create an OOD app step-by-step
  * Simple GUI
  * Simple server application
* Guide: initializers 
* Guide: dashboard customization
  * widgets 
  *Iframe or passenger apps
* Guide: OOD core (advanced)

## Outline of the application creation guide
* Use very basic GUI application (e.g QGIS)
* List of all files needed
  * In Scientific App Development of https://github.com/OSC/ondemand/blob/master/contributor_jam_guide.md
* Basic form.yml[.erb]
  * Loosely based on https://osc.github.io/ood-documentation/latest/tutorials/tutorials-interactive-apps/add-matlab.html, include referencing the the attributes and widgets, https://osc.github.io/ood-documentation/latest/how-tos/app-development/interactive/form.html (this page could be reformatted/expanded into a reference page)
  * Explain how ERB works and how ERB tags can be used to bring in Ruby codes and objects, as in https://github.com/OSC/ondemand/blob/master/contributor_jam_guide.md
  * May be the best to create a reference which includes the form attributes, and context and session objects
* scripts in the template directory (usually simple for VNC apps)
  * explain execution sequence as in https://osc.github.io/ood-documentation/latest/how-tos/app-development/interactive/template.html
* submit.yml.erb
  * based on https://osc.github.io/ood-documentation/latest/how-tos/app-development/interactive/submit.html
  * (for server app) - connection parameters, https://osc.github.io/ood-documentation/latest/how-tos/app-development/interactive/conn-params.html
* view.yml.erb
  * based on https://osc.github.io/ood-documentation/latest/how-tos/app-development/interactive/view.html
  * (for server app) - more details on POST password

