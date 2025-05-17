|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Математическое разложение оценки неопределенности для нейронных сетей
    :Тип научной работы: НИР
    :Автор: Руслан Рашидович Насыров
    :Научный руководитель: к.ф.-м.н., Алексей Алексеевич Зайцев

Abstract
========

Many real-world sequential datasets are irregularly sampled and characterized by a mixture of numerical and categorical features. Such event sequences are critical in domains like healthcare, physics, social media, and finance, where observations arrive continuously over time. Traditional approaches—most notably recurrent neural networks (RNNs)—often discretize time by binning or imputing timestamps, thereby neglecting the underlying continuous dynamics or discarding valuable temporal information. Neural Ordinary Differential Equations (Neural ODEs) offer a principled framework for modeling data in continuous time.

In this thesis, we focus on the unsupervised task of learning embeddings for a marked point process, where each event is assigned a discrete label. We extend the methodology first proposed by~\cite{DM_TPP} in two key ways. First, we replace simple aggregation schemes with a Transformer-based module to capture long-range dependencies more effectively. Second, we introduce a decoupled architecture in which events of each type are processed by separate Neural Controlled Differential Equation (Neural CDE) systems. This design allows the model to accumulate influence at the level of event types—rather than treating every occurrence in isolation—thereby enhancing both representational capacity and interpretability.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
