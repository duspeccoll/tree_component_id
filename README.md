# tree_component_id

Displays component IDs in the Resource tree in ArchivesSpace (versions 2.0+).

Two files here: an extension to *backend/model/large_tree.rb* to include the component IDs (id_0 from the Resource, component_id from the Archival Objects), and a re-write of the container summary populator on the frontend to make sure they display.

Questions: kevin.clair at du.edu
