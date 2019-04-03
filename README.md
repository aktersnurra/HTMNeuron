Depends on the following packages to be included in the main file.

```
\usepackage{tikz}
\usepackage{xcolor}
\usetikzlibrary{matrix,chains,positioning,decorations.pathreplacing,arrows,shapes.gates.logic.US,shapes.gates.logic.IEC,calc}
```

E.g. of usage: 

```
\begin{figure}[ht!]
    \centering
    \hbox{\hspace{5em}\input{PATH_TO_HTMNeuron}}
    \caption{Caption}
    \label{fig:HTMNeuron}
\end{figure}
```

## Ouput 

![Image description](https://github.com/aktersnurra/HTMNeuron/blob/master/htm_neuron.png)
