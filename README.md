
# dataframe2img

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/dataframe2img/master?filepath=index.ipynb)

Makes images of stylized dataframes so that when notebooks are reopened, stylized view represented.

Click on a `launch binder` badge on this page to launch a session where everything needed for this process is set up and the steps in the process are demonstrated.  

[Pandas dataframe styling](https://pandas.pydata.org/pandas-docs/stable/user_guide/style.html) is a great feature for visualizing tabular data right in a notebook; however, it is annoying that it gets removed from rendering when you reopen the notebook. (At least every place I have seen so far for apllied cell and text coloring while `style.format` settings such as `style.format("{:.2%}"` to show floats as percents with two-decimals, seem to survive. Always to be the case for cell and text coloring?) I wanted a way to have at least the information visible when I reload. So an image would at least be viewable, albeit not as interactive.

STEPS:  
Pandas dataframe --> Pandas dataframe with conditional stylized cells ---> Pandas dataframe converted to HTML --> image file --> image viewable when notebook reopened.

-----

Attribution

This builds on the approach from Shovalt [here](https://stackoverflow.com/a/50097322/8508004), with some advanced styling following [Andy Lane's post](https://medium.com/@andy.lane/convert-pandas-dataframes-to-images-using-imgkit-5da7e5108d55).

-----

Click on a `launch binder` badge on this page to launch a session where everything needed for this process is set up and the steps are demonstrated.  

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/dataframe2img/master?filepath=index.ipynb)