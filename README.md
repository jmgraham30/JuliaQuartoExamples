# Julia Quarto Examples

Repository with examples of using [Quarto](https://quarto.org/) with [Julia](https://julialang.org/) for [literate programming](https://en.wikipedia.org/wiki/Literate_programming).

- [Example html document](https://statuesque-kleicha-6d26ad.netlify.app/quarto_html_doc/).

- [Example html presentation](https://statuesque-kleicha-6d26ad.netlify.app/quarto_html_presentation/#/title-slide).

This code base is using the Julia Language and [DrWatson](https://juliadynamics.github.io/DrWatson.jl/stable/)
to make a reproducible scientific project named
> JuliaQuartoExamples

It is authored by JMG.

To (locally) reproduce this project, do the following:

0. Download this code base. Notice that raw data are typically not included in the
   git-history and may need to be downloaded independently.
1. Open a Julia console and do:
   ```
   julia> using Pkg
   julia> Pkg.add("DrWatson") # install globally, for using `quickactivate`
   julia> Pkg.activate("path/to/this/project")
   julia> Pkg.instantiate()
   ```

This will install all necessary packages for you to be able to run the scripts and
everything should work out of the box, including correctly finding local paths.
