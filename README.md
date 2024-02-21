## Persistent Homology
###  <a href="https://ximenafernandez.github.io/">  _Ximena Fernandez_ </a>

Hands on: computational topology in action
This lecture is a live-coding exposition of the use of the software Ripser to compute Persistent Homology, and some real applications with concrete data.

 All the datasets are available at the folder _data_.

 To run the notebooks, it is required to have installed ```jupyter```, as well as the following:
 ``` 
Python (>= 3.6)
NumPy (>= 1.19.1)
SciPy (>= 1.5.0)
scikit-learn (>= 0.23.1)
matplotlib
seaborn
Fermat
```

The specific libraries for TDA we use are:
```
ripser
tadasets
persim
```

The notebook _Intro_Persistent_Homology.ipynb_ provides a complete description and implementation of tools related to the computation of persistent homology with the software ```Ripser```. It also contains  some simulations in synthetic point clouds to describe properties of persistent homology and to infer other topological features from a sample (such as orientability, singularities and local dimension).

The notebooks with the implementation of several applications from the literature can be found at the folder _applications_:
 - _Example_CycloOctane.ipynb_
 - _Example_GridCells.ipynb_
 - _Proteins_Binding.ipynb_
 - _Proteins_Structure_Classification.ipynb_ 

