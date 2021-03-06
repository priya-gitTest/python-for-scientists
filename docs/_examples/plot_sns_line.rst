

.. _sphx_glr__examples_plot_sns_line.py:


Line Plot
=========

Example line plot




.. image:: /_examples/images/sphx_glr_plot_sns_line_001.png
    :align: center





.. code-block:: python

    import matplotlib.pyplot as plt
    import numpy as np
    import seaborn as sns

    sns.set()

    # Initialize a figure and axes object
    fig, ax = plt.subplots(figsize=(3,3))

    # Data
    x = np.linspace(0,100,100)
    y = np.linspace(0,100,100)

    # Add data a scatter points onto axes
    ax.plot(x, y)

    # Name axes
    ax.set_xlabel('x');
    ax.set_ylabel('y');

**Total running time of the script:** ( 0 minutes  0.049 seconds)



.. only :: html

 .. container:: sphx-glr-footer


  .. container:: sphx-glr-download

     :download:`Download Python source code: plot_sns_line.py <plot_sns_line.py>`



  .. container:: sphx-glr-download

     :download:`Download Jupyter notebook: plot_sns_line.ipynb <plot_sns_line.ipynb>`


.. only:: html

 .. rst-class:: sphx-glr-signature

    `Gallery generated by Sphinx-Gallery <https://sphinx-gallery.readthedocs.io>`_
