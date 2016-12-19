

![image alt][1]         


  **Vs**     


  ![image alt][2] 


----------

Installation
-------

 - Jupyter

    Installing Jupyter notebooks on any platform is pretty easy. Most people prefer to use the [anaconda distribution][3] which has been made available by Continuum Analytics. It comes pre loaded with many essential packages in addition to choice of python 2 or 3. 

    The  Anaconda website provides both command line and GUI installers for different platforms making it really comfortable for the user to install. Apart from that, since Jupyter is essentially open source and one can pull from their [github repository][4]. Typical time to install Jupyter and get it up and running will be typically under an hour even for a non technical person. Tech savvy people can accomplish the task in a matter of minutes.

 - Zeppelin

    On the other hand, installing zeppelin is not an easy job. It has a whole lot of things that need to be taken care of and is an extremely time consuming process as well. It requires maven and many other Java libraries in addition to setting up the OS properly. This is a hard task for someone who doesn't have the required technical know how and it can easily consume time in the order of a few hours.

**The winner in the installation department is Jupyter.**

Interface
-------

 - Zeppelin

    Zeppelin has a very good UI and is able to provide a range of functionality to the end user. It looks more up to date and modern. It is intuitive to use as well. The frontend  technology stack is more advanced as it has the ability to provide interactive plotting functionality. This enables zeppelin to take data visualisation to another level.
    An example of visualisation is show below -

![image alt][5]

We can clearly see that zeppelin has good support for spatial data. It has the ability to produce charts just by writing SQL statements or python queries and then choosing an option that we may like. Apart from this ease, what is more important is the fact that these visuals are interactive. This will help in presentations without having to use tools like Tableau.
 
 - Jupyter

    Jupyter does not do a good job in this department. The UI is definitely outdated and there is no option to accommodate interactive plotting function. This can be considered as evidence for the fact that the frontend technology stack is outdated as well.

Below are 2 examples of plots in the Jupyter notebook using the matplotlib library.

![image alt][7]

This is an example of a basic plot in the Jupyter notebook. Although the code to generate the plot itself is not a lot, it still requires extra lines of code.

![image alt][8]

This is an example of advanced 3D plotting in Jupyter. In order to achieve something like the first figure, it will require sufficient amount of extra code. 

As stated earlier, Jupyter doesnt support Interactive visualizations.

**The Winner in the UI department is Zeppelin**

Language and Kernel Support
-------

 - Zeppelin

    Zeppelin has the ability to support some of the important interpreters like Hive, Spark, Cassandra, Postgres and a few others. It also provides the users with ability to write interpreters for platforms it currently doesn't support.

 - Jupyter

    Jupyter has a far more support options with [more than 50 supported kernels][8]. Installing these kernels is also an easy task. If one works in an environment which makes use of a lot of languages, then Jupyter is a better choice.

Although zeppelin has lesser number of supported kernels, it stands out with its ability to integrate code from different languages into the same notebook. That is an amazing functionality which is not present in Jupyter. My verdict however is exclusively based on the number of supported languages.

**The winner in the language support department is Jupyter.** 

 

Community Support
-------

 - Zeppelin

    Zeppelin has been around for 1.5 years and it has been in the incubating stage. Although it is by the the Apache foundation, its growth has been relatively slow. The community base for Zeppelin is not huge.

 - Jupyter

    Jupyter has been around for quite some time now. It has existed for 15 years as "Ipython". Since it is older, it has more users which in turn has resulted in a huge community base and support. Another reason why it is more famous can be its support for almost all important kernels. It is able to attract more and more users because of this fact as well.

**The winner in terms of community support is Jupyter.** 


  [1]: https://raw.githubusercontent.com/jupyter/nature-demo/master/images/jupyter-logo.png
  [2]: https://alexioannides.files.wordpress.com/2016/08/zeppelin1.png?w=640
  [3]: https://www.continuum.io/downloads
  [4]: https://github.com/jupyter/notebook
  [5]: http://image.slidesharecdn.com/alexfossasia20161-160327121115/95/mining-public-datasets-using-opensource-tools-zeppelin-spark-and-juju-26-638.jpg?cb=1459081331
  [6]: https://github.com/ipython/ipython/wiki/IPython-kernels-for-other-languages
  [7]: https://www.packtpub.com/sites/default/files/new_blog_images/Extra_Blogs/notebook_example.png
  [8]: http://itom.bitbucket.org/v2-2-1/docs/_images/matplotlib_intro.png