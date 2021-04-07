## TemperatureTube

TemperatureTube can be used to visualize the temperature of the outer surface of the tube in models of industrial rooms, machines and units, laboratory equipment. The length, diameter and wall thickness of the tube may vary.

The physics of heat transfer processes is calculated based on the solution of the differential equation of the temperature field in the flow.

The calculation of the temperature field is performed every 0.2 seconds, those 5 times per second. Simulators flow rate, flow temperature at the inlet to the tube, ambient temperature are non-stationary and change in time.


Flow rate g(τ) , flow temperature at the inlet to the tube t (τ) and ambient temperature a( τ) independently change over time according to dependence:

g(τ)=a1 +b1×sin (c1× τ)  ,	t (τ)=a2+b2×sin (c2×τ)	,	a( τ)=a3+b3×sin (c3×τ)


a1, b1, c1, a2, b2, c2, a3, b3, c3 - user configurable parameters.


Such the dependence is universal, it can establish constant and variables values of parameters with a wide or narrow range of variation.

Now the tube is made from Steel, and Water flows inside it. Other materials that can be used to make the pipe (for example, Plastic,...), as well as other substances that flow in the pipe (for example, Air,...) can be added.

You can use the [editor on GitHub](https://github.com/software-twins/software-twins.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/software-twins/software-twins.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
