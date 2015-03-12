ArchitecturalTemplates
======================
The Architectural Template method is an efficient design-time engineering method for analyzing scalability, elasticity, and efficiency properties of SaaS applications. This method quantifies such properties based on reusable analysis templates — so called Architectural Templates.
CloudScale includes the Architectural Template language in ScaleDL and provides a catalogue of Architectural Templates specified in this language. CloudScale’s Architectural Templates manifest all quality-relevant characteristics intrinsic to given cloud computing environments. Architects only have to fill-in the parts specific to their concrete SaaS application.


Eclipse Update Sites
-----------------------------------------

##### Nightly Build
- http://cloudscale.xlab.si/cse/updatesites/architecturaltemplates/nightly/


Architectural Template Catalogue
-----------------------------------------
In CloudScale, we collected Architectural Templates for designing and analyzing scalable, elastic, and efficient SaaS applications.

##### Description fo all templates in CloudScale Wiki:
- http://wiki.cloudscale-project.eu/index.php/HowTos

##### Plugin with all template resources:
- org.scaledl.architecturaltemplates.repositories.cloudscale

Example applications of templates
-----------------------------------------
##### Feature
- org.scaledl.architecturaltemplates.examples.feature

##### Included Plugins
- org.scaledl.architecturaltemplates.examples.aliceandbob
- org.scaledl.architecturaltemplates.examples.bookshop
- org.scaledl.architecturaltemplates.examples.cloudstore
- org.scaledl.architecturaltemplates.examples.dynscalingassemblycontext
- org.scaledl.architecturaltemplates.examples.dynscalingcontainer
- org.scaledl.architecturaltemplates.examples.dynverticalscaling
- org.scaledl.architecturaltemplates.examples.onelanebridge

Develop Architectural Templates
-----------------------------------------

1. Download and install [Eclipse Modeling Tools][1]
2. Download and install Eclipse plugin dependencies for Architectural Templates development.
	- Go to Eclipse->Help->Install New Software
	- Add Architectural Templates nightly update site: "http://cloudscale.xlab.si/cse/updatesites/architecturaltemplates/nightly/".
	- Install Architectural Templates feature.
3. Clone repository
	$ git clone https://github.com/CloudScale-Project/ArchitecturalTemplates.git
4. Import Architectural Templates plugins, under "plugins/" directory, into the workbench.


[1]: https://www.eclipse.org/downloads/packages/eclipse-modeling-tools/lunasr2
