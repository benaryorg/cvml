# CVML – CV Markup Language

The CVML (Curriculum Vitae Markup Language) is a language to describe your CV.
You can then build upon this language to create great tools.

# How can I use it?

Using CVML is pretty simple, with this repository a schema file (RELAX NG) is
published that you can easily use to validate files against using tools like
`xmllint`.

# Why not XSD?

XSD is huge and complicated, that is the reason why e.g. `xmllint` supports RNG
better than XSD.
You can also transpile RNG to XSD if you really want to.

# Roadmap

- [ ] create RELAX NG schema
- [ ] automatically generate XSD from RNG
- [ ] build tools
	- [ ] CV generator
	- [ ] CV editor

# License

CVML is licensed under the MIT license for easy and liberal usage.

