# Deep-Learning-Libraries
This Repository Details my Library Skills in Deep Learning

### 1. HyperOpt Library - Used to do Hyperparameter Tuning in ANN

space={
    "lr":hp.loguniform("lr",np.log(1e-5),np.log(1e-1)),
    "momentum":hp.uniform("momentum",0.0,1.0)

}

### From HyperOpt we used hp; It is like Hyperparameter Tuning

### trials=Trials() - This performs HyperParameter Tuning
