This tell us how to estimate contributions of the host galaxy.

#### Flux Variation Gradient(FVG) method

**Basic Principle:** 

Choloniewski, J. 1981, Acta Astron., 31, 293

https://ui.adsabs.harvard.edu/abs/1981AcA....31..293C/abstract



* $\Phi$, total flux

* $f(\nu,t)=n(\nu)g(t)$, the variable component

* $F(\nu)$, the constant component

We assume a two component structure of a spectrum, then 

$$
\Phi(\nu,t) = f(\nu,t)+F(\nu)
$$

$$
f(\nu,t)=n(\nu)g(t), \int_0^\infty n(\nu)d\nu=1.
$$

Then $g(t)$ is a bolometric flux of the variable component. 

In a photometric campaign, we measure the flux in different bands. So, we introduce the transfer/transmission function. Finally, the variable flux can be written as $f_i(t) =\int_{\nu_1}^{\nu_2}n(\nu)S_i (\nu)g(t) d\nu=n_i g(t)$. Rewrite to a vector notation:

$$
{\bf \Phi(t)} ={\bf f(t)}+{\bf F}
$$

$$
{\bf f(t)}={\bf n}g(t)
$$

$$
{\bf \Phi(t)}={\bf n}g(t)+{\bf F}.
$$

Further, the relation between two different bands is

$$
\Phi_k (t) = \frac{n_k}{n_l} \Phi_l (t)+ (F_k -\frac{n_k}{n_l} F_l)
$$

or 

$$
\Phi_k (t)-\frac{n_k}{n_l} \Phi_l (t) =F_k-\frac{n_k}{n_l} F_l.
$$


**So, the intersection area(because of the error) of the AGN and host slopes gives a estimation of  the host contribution.**

For example,Haas, et al.., 2011A&A...535A..73H

http://dx.doi.org/10.1051/0004-6361/201117325

![image-20230323020049690](https://www.aanda.org/articles/aa/full_html/2011/11/aa17325-11/aa17325-11-fig6.jpg)
