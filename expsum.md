---
layout: indepsite
title: $\ell$-adic sheaves toward exponential sums
---

# Student Seminar on $\ell$-adic sheaves toward exponential sums


The goal is to familarize ourselves with $\ell$-adic sheaves and perverse sheaves (complex or $\ell$-adic). The goals are two-fold: 

1. understand Deligne's proof of Weil conjecture/Riemann hypothesis for function fields, and

2. understand cohomological interpretation of exponential sums.

---
## Primary references:

(i)   [Weil Conjectures, Perverse Sheaves and $\ell$-adic Fourier Transform](https://link.springer.com/book/10.1007/978-3-662-04576-3), by Reinhardt Kielhl and Rainer Weissauer

(ii)  [Exponential Sums and $\ell$-adic Cohomology: a Survey](https://link.springer.com/article/10.1007/s11856-000-1278-6), by Gerard Laumon

(iii) [Perverse sheaves and applications to representation theory](https://bookstore.ams.org/surv-258/), by Pramod N. Achar.

Chapter 5 of this contains an quick introduction to $\ell$-adic (perverse) sheaves. Chapter 1 to 3 of this book seems to be a thorough account of complex perverse sheaves.

(iv)  [Weil’s Conjecture for Function Fields I](https://people.math.harvard.edu/~lurie/papers/tamagawa-abridged.pdf), by Dennis Gaitsgory and Jacob Lurie.

This is not the Weil conjecture we are aiming to understand, but the Weil conjecture on the Tamagawa number. Nevertheless, the chapters 2, 3 contain a $\infty$-categorical way of constructing the category of $\ell$-adic sheaves, which seems to be neater than the classical way. A caveat: they in the book require the scheme to be quasi-projective, but most of the results should remain true in the algebraic scheme under some dimension assumption.

(v) [The decomposition theorem, perverse sheaves and the topology of algebraic maps](https://www.ams.org/journals/bull/2009-46-04/S0273-0979-09-01260-9/S0273-0979-09-01260-9.pdf), by Mark Andrea A. De Cataldo and Luca Migliorini.

(vi) [D-Modules, Perverse Sheaves, and Representation Theory](https://link.springer.com/book/10.1007/978-0-8176-4523-6), by Ryoshi Hotta, Kiyoshi Takeuchi and Toshiyuki Tanisaki

---
## Topics related to perverse sheaves.

I want to toss out some applications of perverse sheaves that looks interesting to me. People might also feel motivating from these. 

1. **Function-sheaf dictionary** [(i), Theorem 12.1] provides a correspondence between functions and perverse sheaves over an algebraic scheme over a finite field. In the context of Braverman-Kazhdan program, there is an IC sheaf, namely a simple object in the category of perverse sheaves, that corresponds to the basic function in the positive characteristic case. See [[Ngo20](https://www.math.uchicago.edu/~ngo/takagi.pdf)].

2. **Weights** [(i), $\S$ 1], more or less the eigenvalues of Frobinius, along with the **Grothendieck's trace formula** allow us to interpret a complete exponential sum as an alternating sum of dimensions of $\ell$-adic cohomologies. The main tools here are **Deligne-Fourier transform** and Artin-Schreier sheaves. See [(ii)] and [(i), $\S$ 5].
 
3. **Geometric Langlands** and **geometric representation theory**. These I don't know well, but they are function field version of the classical Langlands over number fields. The common language used in that realm is surely perverse sheaves. For me I would like to know what is the content of geometric Satake, or derived Satake.

4. **Fundamental lemma**. As the same suggested, it is one of the fundamental lemma in matching of local orbital integrals. By the work of Waldspurper, the problem is reduced to the local positive characteristic case. It is finally proved by Ngo, which earns him a Field medal. For the history and the tools used, see [[Ngo10](https://www.math.uchicago.edu/~ngo/ICM.pdf)] and [(v), $\S$ 4.6].

5. **Riemann-Hilbert correspondence** gives an equivalence bewteen perverse sheaves and regular holonomic $D$-module, invented by Saito and Kashiwara. Please refer to [(vi)] because I don't know well on this.

