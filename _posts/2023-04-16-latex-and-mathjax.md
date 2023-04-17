---
layout: post
title: Latex and Mathjax
author: Tri-Nhu
---

Let $Y$ be an RV following a Gamma distribution, 
parameterized by $\alpha$ and $\theta$, 
with PDF and CDF, respectively, 
given by 


$$
\begin{align}
	f_Y (y ; \alpha, \theta) &= \frac{1}{\Gamma(\alpha) \theta^\alpha} y^{\alpha - 1} \exp \left( -\frac{y}{\theta}\right), y \geq 0, \label{PDF_Gamma} \\
	F_Y (y ; \alpha, \theta) &= \frac{1}{\Gamma(\alpha)} \gamma\left( \alpha, \frac{y}{\theta}\right), y \geq 0 . \label{CDF_Gamma}
\end{align}
$$

Matrix:

$$
\renewcommand{\vec}[1]{\boldsymbol{\mathrm{#1}}}
\newcommand{\hub}{\mathsf{H}}
\newcommand{\user}{\mathrm{U}}
\newcommand{\Tx}{\mathrm{T}}
\newcommand{\Rx}{\mathrm{R}}
\newcommand{\jammer}{\mathrm{J}}
\newcommand{\snr}{\mathtt{SNR}}
\newcommand{\ccch}{\mathrm{C}}
\newcommand{\data}{\mathrm{D}}
\begin{align} 
	\vec{H} = 
	\begin{bmatrix}
	    \tilde{h}_{\hub}^{f_1} &  \dots  & \tilde{h}_{\hub}^{f_k}  & \dots &\tilde{h}_{\hub}^{f_K} \\
	    \tilde{h}_{\Tx_1 \Rx_1}^{f_1} &  \dots  & \tilde{h}_{\Tx_1 \Rx_1}^{f_k}  & \dots &\tilde{h}_{\Tx_1 \Rx_1}^{f_K} \\
	    \vdots & \vdots & \vdots & \ddots & \vdots \\
	    \tilde{h}_{\Tx_n \Rx_n}^{f_1} &  \dots  & \tilde{h}_{\Tx_n \Rx_n}^{f_k}  & \dots &\tilde{h}_{\Tx_n \Rx_n}^{f_K} \\
	    \vdots & \vdots & \vdots & \ddots & \vdots \\
	    \tilde{h}_{\Tx_N \Rx_N}^{f_1} &  \dots  & \tilde{h}_{\Tx_N \Rx_N}^{f_k}  & \dots &\tilde{h}_{\Tx_N \Rx_N}^{f_K} \\
	\end{bmatrix},
\end{align}
$$


## Reference  
- [Jekyll with Mathjax](https://scaomath.github.io/blog/welcome-to-jekyll/)