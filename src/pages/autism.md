---
title: Autism
menus:
  main:
    title: AU
template: docs
---
componentDidMount: The editor will load an empty EditorState if a note does not exist in our database. If a note does exist in our database, we use convertFromRow and JSON.parse to transform the data from our database into an immutable object so that it can be load as the contents of the note into the editor
