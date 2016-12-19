

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

 - Jupyter

    Jupyter does not do a good job in this department. The UI is definitely outdated and there is no option to accommodate interactive plotting function. This can be considered as evidence for the fact that the frontend technology stack is outdated as well.

**The Winner in the UI department is Zeppelin**

Language and Kernel Support
-------

 - Zeppelin

    Zeppelin has the ability to support some of the important interpreters like Hive, Spark, Cassandra, Postgres and a few others. It also provides the users with ability to write interpreters for platforms it currently doesn't support.

 - Jupyter

    Jupyter has a far more support options with [more than 50 supported kernels][5]. Installing these kernels is also an easy task. If one works in an environment which makes use of a lot of languages, then Jupyter is a better choice.

Although zeppelin has lesser number of supported kernels, it stands out with its ability to integrate code from different languages into the same notebook. That is an amazing functionality which is not present in Jupyter. My verdict however is exclusively based on the number of supported languages.

**The winner in the language support department is Jupyter.** 

 


  [1]: https://raw.githubusercontent.com/jupyter/nature-demo/master/images/jupyter-logo.png
  [2]: https://alexioannides.files.wordpress.com/2016/08/zeppelin1.png?w=640
  [3]: https://www.continuum.io/downloads
  [4]: https://github.com/jupyter/notebook
  [5]: https://github.com/ipython/ipython/wiki/IPython-kernels-for-other-languages