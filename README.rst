|test| |codecov| |docs|

.. |test| image:: https://github.com/Intelligent-Systems-Phystech/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/Intelligent-Systems-Phystech/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/Intelligent-Systems-Phystech/ProjectTemplate/master
    :target: https://app.codecov.io/gh/Intelligent-Systems-Phystech/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/Intelligent-Systems-Phystech/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intelligent-systems-phystech.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Понижение размерности пространства обучаемых параметров в задаче адаптации модели к домену
    :Тип научной работы: НИР
    :Автор: Ремизова Анна Вадимовна
    :Научный руководитель: к.ф.-м.н. Грабовой Андрей Валериевич

Abstract
========

В данной работе исследуется способ уменьшения размерности пространства обучаемых параметров в задаче детектирования ai текстов(задача многоклассовой классификации). Для fine tuning использовалась модель RoBerta с LoRA адаптером. Было проведе- но несколько экспериментов, чтобы выяснить, является ли исполь- зование LoRA для аппроксимации матрицы весов эффективным с точки зрения времени, ресурсов или точности. Было показано, что при меньших ресурсах модель distilled RoBerta base с LoRA адапте- ром может получить те же показатели метрик для классификации текстов, написанных человеком, что и vanilla distilled RoBerta base на наборе данных с 4 классами.

Keywords: MachineLearning,AudioStyletransfer,SpeechStyletransfer,ImageStyle Transfer, Deep Convolutional NN, Gram Matrix, Linear Transformation

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/Intelligent-Systems-Phystech/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.com/intsystems/Remizova-BS-Thesis/blob/master/code/baseline.ipynb>`_. Can use `kaggle notebook <https://www.kaggle.com/code/annaremi/baseline>`_.
