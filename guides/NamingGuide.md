# About Names

- [Best Practice](https://github.com/JuliaPraxis/Naming/blob/master/guides/NamingGuide.md#best-practice)
- [Our Conventions](https://github.com/JuliaPraxis/Naming/blob/master/guides/NamingGuide.md#our-conventions)
- [Shortend Forms](https://github.com/JuliaPraxis/Naming/blob/master/guides/NamingGuide.md#shortend-forms)
- [For Reference](https://github.com/JuliaPraxis/Naming/blob/master/guides/NamingGuide.md#for-reference)

-------

## Best Practice

- Prefer clarity to brevity  
  - :ok:  VectorArithmetic, dominant_gene
  - :x:  VecArith, dominant

- Prefer specificity to generality  
  - :ok:  VectorArithmetic
  - :x:  VectorProcessing
  
- prefer familiarity to jargon   
  - :ok:  ColorVision
  - :x:  TristimulusEncoding

- Be consistent
  - :ok:  get_direction, get_angle
  - :x:  get_direction, derive_angle
  
- Use singular terms for individuals and members of an aggregate
  - :ok: gravitational_flux
  - :x: gravity_flux

- Use collective terms for aggregations and subsumptive grouping
  - :ok: orbital_frequencies
  - :x: orbitals_frequency

- Use acronyms only when there is no chance of confusion
  - :ok:  ParseHTML, two_line_element
  - :x:  ParseHypertextMarkupLanguage, tle

- Do not use "Julia" in names
  - :ok:  Lint
  - :x:  LintJulia

## Our Conventions

- Name packages, module and types using titlecase  
  - :ok:  Space, SpaceTime
  - :x:  space, spaceTime

- Name functions and variables using lowercase  
  with __'\_'__ as a word separator unless words are short
  - :ok:  abserr, abs_error, build_robot
  - :x:  abserror, buildRobot
  
- Name constants using uppercase  
  with __'\_'__ as a word separator almost always
  - :ok:  GREEN, NEW_SOCKET
  - :x:  Green, NEWSOCKET

- Use the plural form to package a type
  - :ok:  Robots
  - :x:  Robot

- Use the singular form to define a type
  - :ok:  Robot
  - :x:  Robots

- For package, module or type names with an initial acronym  
  write the acronym in uppercase then use camelecase:
  - :ok:  CSSparser, HTMLtagChecker
  - :x:  CSSParser, HTMLTagChecker
  
## Shortend Forms

- Some abbreviations appear often.  Using these forms simplifies collaboration.   

  - [Useful Abbreviations](https://github.com/JuliaPraxis/Naming/blob/master/guides/ShortForms.md#table-of-abbreviations)
  - [Useful Abbreviations, sorted](https://github.com/JuliaPraxis/Naming/blob/master/guides/ShortForms.md#alphabetical-table)
   
## For Reference

- The User Manual

  - [Package Names](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package)
  - [Function Names](http://docs.julialang.org/en/latest/manual/style-guide/#use-naming-conventions-consistent-with-julia-s-base)
