---

widget: portfolio
headless: true  # This file represents a page section.
weight: 20
# ... Put Your Section Options Here (title etc.) ...
title: Publications
content:
  # Page type to display. E.g. project.
  page_type: publication

# Uncomment to only show content with specific tags
#  filters:
#    tags:
#      - featured project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Mouse
      tag: mouse
    - name: Primate
      tag: primate
    - name: Zebra fish
      tag: zebrafish
    - name: Avian
      tag: avian
    - name: Invertebrate
      tag: invertebrate
    - name: Vertebrate
      tag: vertebrate
    - name: Photoreceptors
      tag: photoreceptors
    - name: horizontal cells
      tag: horizontalcells
    - name: bipolar cells
      tag: bipolarcells
    - name: amacrine cells
      tag: amacrinecells
    - name: RGCs
      tag: rgcs
    - name: Structure
      tag: structure
    - name: Function
      tag: function
    - name: Molecular
      tag: molecular 
    - name: Injury/disesase
      tag: inurydisease
    - name: Outer retina
      tag: outerretina
    - name: Inner retina
      tag: innerretina
    - name: RPE/Glia
      tag: rpeglia
    - name: Computational
      tag: computational 
    - name: Organoid
      tag: organoid
    - name: Other
      tag: other
 
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact  
  #   3 = Card
  #   5 = Showcase
  view: 2
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false

---

