= Composer Documentation Set

This set of documentation is designed to be build with link:https://github.com/mulesoft/docs-site-comity[comity].

It follows a less complex structure than antora projects.

[cols=2*, options=header]
|===
|what
|where

|AsciiDoc files
|`src/docs`

|Images
|`src/docs/images`

|Share only content
|`src/docs/includes`
|===

At this point in time, there is no need to create a playbook, but that could change.

== Notes
* The table of contents design isn't complete; suggested in the meantime to create nav.adoc as for antora projects
* When comity is ready for testing, use the instructions there for building content.
