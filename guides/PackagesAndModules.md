# Naming Packages and Modules

- Use titlecase
  - :ok: CategoryTheory
  - :x:  categorytheory, categoryTheory
  
- Prefer clarity to brevity  
  - :ok: VectorArithmetic
  - :x:  VecArith
  
- Prefer specificity to generality  
  - :ok: VectorArithmetic
  - :x:  VectorProcessing

- Prefer the familiar to jargon  
  - :ok: ColorVision
  - :x:  TristimulusEncoding

- Prefer plural to singular when packaging a type
  - :ok: ProjectiveReals
  - :x:  ProjectiveReal

- Do not use "Julia" in the package name
  - :ok: CategoryTheory
  - :x:  CategoryTheoryForJulia

- Use acronyms only when there is no chance of confusion
  - :ok: ParseHTML, GraphModellingLanguage
  - :x: ParseHypertextMarkupLanguage, GML

- For package, module or type names with an initial acronym  
  write the acronym in uppercase then use titlecase
  - :ok:  CSSParser, HTMLBodyValidator
  - :x:  CSSparser, HTMLbodyValidator   
  - **note:** the Praxis group would prefer the manual allow titlecase: CssParser, HtmlBodyValidator
 ------

    
Please see [the manual](http://docs.julialang.org/en/latest/manual/packages/#guidelines-for-naming-a-package).


  
