# fractoolbox

Python tools for structural geology and borehole image analysis that includes data handling, frequency and geometric analysis, and reservoir geomechanics.  

fractoolbox is in rapid development so the content of this repo will change regularly and may not be stable. We welcome use of the fractoolbox libraries and notebooks but only on an 'as is' basis and without any warranty implied. 

The Juypter Notebooks (.ipynb) are step-by-step walkthroughs of fractoolbox and other related libraries (such as mplstereonet). Some also describe the theory underlying the tools and point readers to relevant academic literature. If you are new to fractoolbox, these are a good place to start.

Made for Python 3.3+

### Explore without installation or download

Click on the icon below to launch an instance of fractoolbox in your web browser. It may take a couple of minutes to load but binder will allow you to interact with fractoolbox without downloading or installing anything on your machine. 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ICWallis/fractoolbox/master)

It may take longer than usual for binder to load the interactive environment because fractoolbox is currently changed regularly and the environment will be built from scratch. 

### New to python? Start here.

If you're new to python, download the 'Python for Geoscientists' course from [here](https://github.com/ddempsey/python_for_geoscientists) because it includes a quick-start guide and will set you on the pythonic path.  

We recommend starting by downloading [Anaconda](https://www.anaconda.com/) to manage Python and Juypter Notebook installation because it comes with many of packages/libraries required by fractoolbox already baked in.  

There are two libraries used in fractoolbox that do not come standard with the Annaconda build. Once you you have installed Annaconda, these libraries may be installed by command-line:

> $ pip install mplstereonet

> https://github.com/joferkington/mplstereonet

Due to compatibility with resent versions of matplotlib, ensure you have mplstereonet version 0.6 or later.

> $ pip install seaborn

> https://seaborn.pydata.org/

When mplstereonet is used after seaborn, there may be an issue with mplstereonet drawing plot elements like the grid. If this occurs, use sns.reset_defaults() just prior to building a stereonet with mplstereonet. 

Now you're set up, use the green 'Code' button on this page to download a copy of this git repository. Unzip and have fun exploring your own fracture data. 

### License

Apache 2.0 

https://choosealicense.com/licenses/apache-2.0/

### Development

To date, the content of fractoolbox has been generated during doctoral research undertaken by [Irene Wallis](https://www.cubicearth.nz/), which is supervised by [David Dempsey](https://sites.google.com/view/dempsey-research-group/home) and [Julie (JR) Rowland](http://www.science.auckland.ac.nz/people/profile/j-rowland)  and includes code/math contributions from [Evert Durán](https://unidirectory.auckland.ac.nz/profile/e-quintero). The paper below illustrates use of these tools to interpret borehole image data acquired in high-temperature geothermal wells. 

Wallis, I.C., Rowland, J. V. and Dempsey, D. E., Allan, G., Sidik, R., Martikno, R., McLean, K., Sihotang, M., Azis, M. and Baroek, M. 2020 (submitted) Approaches to imaging feedzone diversity with case studies from Sumatra, Indonesia, and the Taupō Volcanic Zone, New Zealand. New Zealand Geothermal Workshop: Waitangi, New Zealand.


Feedback and contributions welcome.