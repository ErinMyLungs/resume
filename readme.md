# Erin's Resume in LaTeX

A basic modular resume repo setup in LaTeX. `example_resume_output.pdf` contains an example resume with faked contact info.

## Structure
* `resume.tex` - 
  * This imports each section and sets styling options.
  * Look at [moderncv](https://github.com/xdanaux/moderncv) for specifics to tweak.
* `contact` - contains contact info
  * I have variants with more or less personal info depending on where I'm posting my resume.
* `employment` - contains employment history
  * `employment_section.tex` imports each individual job section
  * `jobs/`
    * Job descriptions go here, typically with `\cventry{}` or `\cvitem` commands.
  * `skills` - contains skill lists
    * `skills_section.tex` selects specific skill lists to include as columns
      * These are basic `\begin{itemize}` lists

