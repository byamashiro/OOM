# Website

**Table of Contents**

- [Current Tasks](#tasks)
- [Event List](#event-list)
- [Plots](#plots)

# Tasks
- [ ] Set up a script to reduce data files into easily readable formats for the bokeh script
  - [ ] Proton Flux
  - [ ] Xray Flux
  - [ ] Neutron Monitor
- [ ] Set up comparisons between event dates rather than data sets
- [ ] Translate bokeh figures into axes objects
- [ ] Generate event list in a table


# Event List

|	Symbol		    | Description  | Value | Unit |   | Links
|:--------------|:----------------------|:--------------|:----------|:--------------|:--------------|
|	AU           			|	Astronomical Unit	|	1.496 (11)	|	$$m$$            	|				|  [Flux Data](/_includes/test.html)   |
|	L$$_{\odot}$$			|	Solar luminosity 	|	3.85 (26) 	|	$$J\cdot s^{-1}$$	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |
|	             			|	                 	|	          	|	                 	|				|  [Flux Data](/_includes/test.html)   |

# Plots

## CDN Option
{% include proton_plot.html %}


### Using Bokeh
In the "daily" directory, use the following command. The "main.py" file must be in the directory above the nested "daily" directory.
- [Comparison Plot](/_includes/proton_plot.html)
- [Individual Plot](/_includes/proton_plot_individual.html)

<details><summary>Bokeh Server</summary>
<p>

```bash
bokeh serve .
```

</p>
</details>




---
# Reference Markdown
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```