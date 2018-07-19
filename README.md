# The Formation of Extractive Structures in Networks

## 1 About

This directory contains a set of TeX files which, when compiled into a PDF, the paper **The Formation of Extractive Structures in Networks**. The paper provides an analysis of central and critical nodes within a general network topology. The full paper can be found in [`BlockFormation.pdf`](./BlockFormation.pdf).

### 1.1 Abstract

This article develops and assesses the notions of block formation within a topological structure. We quote the abstract of the article below.

> It is well-known that critical nodes or "middlemen" control information flows in a directed network and take advantage of these positions to extract excess rents from these networks. We extend this concept to _critical node sets_ and investigate the potential contestation of these critical node sets by other node sets. This methodology allows us to introduce a game theoretic approach to analyse the formation of these critical node sets and allows the introduction of new _network centrality measures_ that are based on potential membership of these critical node sets.
>
> We introduce a non-cooperative game theoretic approach to network centrality based on the formation of certain critical node sets. We show that the Strong Nash equilibrium in a critical node set formation game identifies the maximally controlling critical node sets in any network. This provides a foundation to an innovative way of identifying brokerage structures in directed networks. We develop applications to the Renaissance Florentine elite network and the networks formed by the 9/11 terrorists.

## 2 Compiling the article

The latest PDF should have already been compiled and uploaded to the repository. If the latest PDF has not been compiled, or to make changes and compile yourself, you must have a LaTeX executable installed on your system.

* For Windows I suggest using [MiKTex](http://miktex.org/download),
* For Mac OSX I suggest using [MacTeX](https://tug.org/mactex/), and
* For Ubuntu Linux I suggest using [TeX Live](https://help.ubuntu.com/community/LaTeX).

## 3 Network visualisation

All networks, and some of the analysis, were rendered with the `Gephi` software package which can be found [here](https://gephi.org/). I created a wrapper for `Gephi` such that data generated in `R` could be passed between it and `Gephi`.

## 4 Contact

Please contact [me](mailto:sims.owen@gmail.com) with regards any issues or queries that you have.
