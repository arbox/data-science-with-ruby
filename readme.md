<img src="header.png" align="center">

[[RubyNLP](https://github.com/arbox/nlp-with-ruby) |
 [RubyML](https://github.com/arbox/machine-learning-with-ruby) |
 [RubyInterop](https://github.com/arbox/ruby-interoperability)]


# Awesome Data Science with Ruby [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Links and Resources for Data Processing in Ruby

This curated list comprises [_awesome_][awesome] tutorials, libraries,
information sources about various Data Science applications using
the [Ruby programming language][ruby].

A lot of useful resources on this list come from the development by
[The Ruby Science Foundation][sciruby], our [contributors][contributors] and
our own day to day work on various data intensive applications.
Read [why](#wait-but-why) this list is awesome.

:sparkles: Every [contribution](#contributing) is welcome!
Add links through pull requests or create an issue to start a discussion.

Follow us on [Twitter](https://twitter.com/RubyNLP)
and please spread the word using the `#RubyDataScience` hash tag!

<!-- nodoc -->

## Contents

<!-- toc -->

- [Ruby versus Python](#ruby-versus-python)
- [Statistics](#statistics)
- [Symbolic Computation](#symbolic-computation)
- [Visualization](#visualization)
- [Interactive Computing](#interactive-computing)
- [Input and Output](#input-and-output)
  * [General formats](#general-formats)
  * [Database Adapters](#database-adapters)
  * [Domain specific formats](#domain-specific-formats)
- [Provisioning Infrastructure](#provisioning-infrastructure)
- [Machine Learning](#machine-learning)
- [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
- [Contributing](#contributing)
- [Wait but why?](#wait-but-why)
- [License](#license)

<!-- tocstop -->

<!-- doc -->

## Ruby versus Python

| Ruby   | Python |
| ---    | ---    |
| Daru   | Pandas |

## Statistics

- [simple_stats](https://github.com/brianhempel/simple_stats) -
  `Enumerable` patches for descriptive statistics.
- [enumerable-statistics](https://github.com/mrkn/enumerable-statistics) -
  Fast implementation of descriptive statistics for the `Enumerable` module.
- https://github.com/SciRuby/daru
- [statsample](https://github.com/sciruby/statsample) -
  A suite for basic and advanced statistics on Ruby. <sup>[[dep: GLS](#gls)]</sup>
- https://github.com/sciruby/statsample-glm
- https://github.com/sciruby/statsample-bivariate-extension
- https://github.com/sciruby/statsample-timeseries
- [statistics2](https://github.com/abscondment/statistics2) -
  Provides normal, Chi-square, t- and F- probability distributions for Ruby.
- [rb-gsl](https://github.com/blackwinter/rb-gsl) -
  Ruby interface to the GNU Scientific Library. <sup>[[dep: GLS](#gls)]</sup>
- [PCA](https://github.com/gbuesing/pca) - Principal component analysis (PCA) in Ruby.
- https://github.com/jtescher/descriptive-statistics
- https://github.com/sciruby/distribution

## Symbolic Computation

- https://github.com/symengine/symengine

## Visualization

Comprehensive tools for Data Visualization.

- [matplotlib](https://github.com/mrkn/matplotlib.rb) -
  Ruby based wrapper around [matplotlib](https://matplotlib.org/).
   <dep>[[dep: matplotlib](#matplotlib)]</dep>
- [mathematical](https://github.com/gjtorikian/mathematical) -
  PNG and MathML renderings for your equations.
- https://github.com/v0dro/benchmark-plot
- https://github.com/domitry/Nyaplotjs
- https://github.com/domitry/nyaplot
- https://github.com/SciRuby/gnuplotrb
- [ruby-graphviz](https://github.com/glejeune/Ruby-Graphviz)
  <sup>[[dep: Graphviz](#graphviz)]</sup>
- [gnuplot](https://github.com/rdp/ruby_gnuplot/tree/master)
  <sup>[[dep: gnuplot](#gnuplot)]</sup>
- https://github.com/zuhao/plotrb
- https://github.com/brasten/scruffy
- https://github.com/zverok/worldize
- https://github.com/masa16/ruby-mathgl

## Interactive Computing

- [iruby-rails](https://github.com/mrkn/iruby-rails) -
  Integration library for IRuby and Rails.
- https://github.com/sciruby/iruby

## Input and Output

### General formats

- https://github.com/fiksu/rcsv
- [ox](https://github.com/ohler55/ox) -
  Optimized for speed XML parser and object marshaller.
- [oj](https://github.com/ohler55/oj) -
  High-speed JSON parser.
- Markdown
- Nokogiri
- CSV

### Database Adapters

- pg
- Mongo
- MySQL

### Domain specific formats

- BibTeX

## Provisioning Infrastructure

- https://github.com/mrkn/gpu-instance
- https://github.com/mrkn/computing_node
- https://github.com/k1LoW/awspec


## Machine Learning

Please look at our extensive [Awesome ML with Ruby][ml-with-ruby] list.

## Articles, Posts, Talks, and Presentations

- 2017
- 2016
  - _Scientific Computation and Data Visualization with Ruby_ by [Sameer Deshmukh](https://twitter.com/v0dro)
    <sup>[[slides](https://www.slideshare.net/SrijanOne/webinar-scientific-computation-and-data-visualization-with-ruby) |
          [video](https://www.youtube.com/watch?v=5970kC6MfBE)]</sup>
- 2015
- 2014
- 2013
- 2012
- 2011
- 2010
  - _NArray and scientific computing with Ruby_ by [Masahiro Tanaka](https://twitter.com/masa16tanaka)
    <sup>[[video](https://vimeo.com/14823720) |
          [slides](https://www.slideshare.net/masa16tanaka/narray-and-scientific-computing-with-ruby)]</sup>

## Contributing

:sparkles: We are very glad to see you in this section! :sparkles:

Before you go ahead you should know that your contributions will be published under
the terms of the [`CC0` license](https://creativecommons.org/publicdomain/zero/1.0/).

Have you just found a spelling error? Need to fix indentation?
Send us a pull request! :sparkles:

You have discovered something cool, but don't know exactly if it suits the
awesome definition? :+1: Submit a pull request to the [inbox](inbox.md)!
We'll consider your addition and format it for you! :smiley:

:boom: If you know something pretty cool, it suits the awesome definition, works for you
and seems to be useful for the community please add it to the [main list](README.md).
In this case please ensure your pull request adheres to the following guidelines:

- Use one commit per addition (several commits per PR are OK).
- Add everything to the bottom of the relevant category.
- If required introduce new categories or improve the existing categorization.
- Use the following format: `- [title](link) - Distinguishing Description. <sup>[additional links]</sup>`
- Name the libraries exactly how they are required from the Ruby program, not
  after the Readme's title, e.g. `treat`, not `Treat`, since you do `require "treat"`.
- Break down long lines, check your spelling, capitalization, and punctuation.
- Provide a useful titles and comments for your Pull Request (not `Changed readme.md`),
  mention the originator in the commit message if possible, e.g. `Added the neuroevo lib by @giuse.`
- Add the topic `rubydatascience` to your repository or open an issue and
  kindly ask the originator of the project to do so (if applicable for your submission).

Sometimes we will ask you to edit your Pull Request before it is included.
This is normally due to spelling errors or because your PR didn't match
these guidelines.

[Here][change-pr] is a write up on how to change a Pull Request and
the different ways you can do that.

:+1: Thank you for your suggestions!

## Wait but why?

There are a lot of software lists with tools related to the Data Science.
There are a couple of lists with Ruby related projects. There are no lists of
only working and tested software with documented scope. We'll try to make one!

What is awesome? Awesome are documented, maintained and focused tools.

Can something turn not awesome at a point? Yes! Abandoned projects with broken
dependencies aren't awesome any more! They leave this list.

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) `Awesome Data Science with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors][contributors].

To the extent possible under law, the person who associated CC0 with
`Awesome Data Science with Ruby` has waived all copyright and related or neighboring rights
to `Awesome Data Science with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->
[ruby]: https://www.ruby-lang.org/en/
[ml-with-ruby]: https://github.com/arbox/machine-learning-with-ruby
[awesome]: https://github.com/sindresorhus/awesome/blob/master/awesome.md
[change-pr]: https://github.com/RichardLitt/knowledge/blob/master/amending-a-commit-guide.md
[sciruby]: https://github.com/sciruby
[contributors]: https://github.com/arbox/data-science-with-ruby/graphs/contributors
