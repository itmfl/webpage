+++
# Custom widget.
# An example of using the custom widget to create your own homepage section.
# To create more sections, duplicate this file and edit the values below as desired.
widget = "custom"
active = true
date = 2018-08-01T00:00:00

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Statistical inference on graphs"
subtitle = ""

# Order that this section will appear in.
weight = 60

+++
## Course description
The course provides an introduction to and overview of current research in
random graph inference, with a particular focus on spectral methods and their
applications to inference for independent-edge random graphs. Topics include
concentration inequalities; analysis of matrix perturbations; spectral
decompositions of graph adjacency and Laplacian matrices; consistent estimation
of latent variables associated to vertices; clustering, community detection,
and classification in networks; and multi-sample hypothesis testing for graphs.
Emphasis will be on a framework for establishing classical
properties---consistency, normality, and efficiency---for estimators of graph
parameters. Students will read papers in the literature and are expected to
participate actively in class. Recommended prerequisites [EN.553.792](http://e-catalog.jhu.edu/departments-program-requirements-and-courses/engineering/applied-mathematics-statistics/#courseinventory) 
and [EN.553.630](http://e-catalog.jhu.edu/departments-program-requirements-and-courses/engineering/applied-mathematics-statistics/#courseinventory). 

## Instructors and TA
+ [Avanti Athreya](https://engineering.jhu.edu/ams/faculty/avanti-athreya/). Email: dathrey1 dot jhu dot edu
   - Office Hours: Monday 3pm--5pm in Whitehead Hall 306D
+ [Minh Tang](https://www.cis.jhu.edu/~minh). Email: mtang10 dot jhu dot edu
   - Office Hours: Friday 2pm--4pm in Whitehead Hall 306E
+ [Joshua Cape](https://pages.jh.edu/~jcape1). Email: jcape1 dot jhu dot edu 
   - Office Hours: TBD in Whitehead 212

## Syllabus and tentative schedule

Date       | Topics  | Readings
-----------|-------- |---------
08/30 | Introduction and overview | 
08/31 | Random graphs models: Erdos-Renyi, stochastic blockmodels, preferential attachments | [Bollobas et al.](https://arxiv.org/abs/math/0504589), [Hoff et al.](https://www.stat.washington.edu/raftery/Research/PDF/hoff2002.pdf), [Chung and Lu](http://www.math.ucsd.edu/~fan/complex/ch3.pdf)
09/05 | Random dot product graphs, adjacency and Laplacian spectral embedding | [Athreya et al.](https://arxiv.org/abs/1709.05454)
09/07 | Matrix concentration inequalities | [Oliviera](https://arxiv.org/abs/0911.0600), [Tropp](https://arxiv.org/abs/1004.4389), [Lu and Peng](http://www.combinatorics.org/ojs/index.php/eljc/article/view/v20i4p27) 
09/10 | Matrix concentration inequalities (day 2) | [Oliviera](https://arxiv.org/abs/0911.0600), [Tropp](https://arxiv.org/abs/1004.4389), [Lu and Peng](http://www.combinatorics.org/ojs/index.php/eljc/article/view/v20i4p27) 
09/12 | Matrix concentration inequalities (day 3) |  [Oliviera](https://arxiv.org/abs/0911.0600), [Tropp](https://arxiv.org/abs/1004.4389), [Lu and Peng](http://www.combinatorics.org/ojs/index.php/eljc/article/view/v20i4p27) 
09/14 | Subspace perturbation | [Yu et al.](https://arxiv.org/abs/1405.0680), [Rohe et al.](https://arxiv.org/abs/1007.1684)
09/17 | Subspace perturbation (day 2) | [Yu et al.](https://arxiv.org/abs/1405.0680), [Rohe et al.](https://arxiv.org/abs/1007.1684)
09/19 | Subspace perturbation (day 3) | [Cai and Zhang](https://arxiv.org/abs/1605.00353) 
09/21 | Clustering and spectral clustering | [von Luxburg](https://arxiv.org/abs/0711.0189)
09/24 | Clustering and spectral clustering (day 2) | [Belkin and Niyogi](http://web.cse.ohio-state.edu/~belkin.8/papers/LEM_NIPS_01.pdf), [Coifman and Lafon](https://www.sciencedirect.com/science/article/pii/S1063520306000546)
09/26 | Clustering and spectral clustering (day 3) | [von Luxburg et al.](https://arxiv.org/abs/0804.0678)
09/28 | Estimation and consistency in stochastic blockmodel and random dot product graphs | [Sussman et al.](https://arxiv.org/abs/1108.2228), [Sussman et al.](https://arxiv.org/abs/1207.6745), [Rohe et al.](https://arxiv.org/abs/1007.1684)
10/01 | Estimation and consistency in stochastic blockmodel and random dot product graphs (day 2) | [Lyzinski et al.](https://arxiv.org/abs/1310.0532)
10/03 | Estimation and consistency in stochastic blockmodel and random dot product graphs (day 3) | [Lyzinski et al.](https://arxiv.org/abs/1503.02115), [Cape et al.](https://arxiv.org/abs/1705.10735)
10/05 | A central limit theorem for scaled eigenvectors of random dot product graphs | [Athreya et al.](https://arxiv.org/abs/1305.7388)
10/08 | Limit theorems for eigenvectors of the normalized Laplacian for random graphs | [Tang and Priebe](https://arxiv.org/abs/1607.08601), [Chernoff](https://projecteuclid.org/euclid.aoms/1177729330), [Sarkar and Bickel](https://arxiv.org/abs/1310.1495)
10/10 | Limit theorems for eigenvectors of the normalized Laplacian for random graphs (day 2) | [Tang and Priebe](https://arxiv.org/abs/1607.08601), [Chernoff](https://projecteuclid.org/euclid.aoms/1177729330), [Sarkar and Bickel](https://arxiv.org/abs/1310.1495)
10/12 | Limit theorems for eigenvectors of the normalized Laplacian for random graphs (day 3) | [Tang and Priebe](https://arxiv.org/abs/1607.08601), [Chernoff](https://projecteuclid.org/euclid.aoms/1177729330), [Sarkar and Bickel](https://arxiv.org/abs/1310.1495)
10/15 | Asymptotically efficient estimators for stochastic blockmodels | [Bickel et al.](https://arxiv.org/abs/1207.0865), [Tang et al.](https://arxiv.org/abs/1710.10936)
10/17 | Asymptotically efficient estimators for stochastic blockmodels (day 2) | [Bickel et al.](https://arxiv.org/abs/1207.0865), [Tang et al.](https://arxiv.org/abs/1710.10936)
10/19 | Fall break | [Candide, ou l'Optimisme](https://www.gutenberg.org/files/19942/19942-h/19942-h.htm)
10/22 | Asymptotically efficient estimators for stochastic blockmodels (day 3) | [Bickel et al.](https://arxiv.org/abs/1207.0865), [Tang et al.](https://arxiv.org/abs/1710.10936)
10/24 | Two-sample semiparametric testing for random graphs | [Tang et al.](https://arxiv.org/abs/1403.7249)
10/26 | Two-sample semiparametric testing for random graphs (day 2) | [Tang et al.](https://arxiv.org/abs/1403.7249)
10/29 | Two-sample semiparametric testing for random graphs (day 3) | [Levin et al.](https://arxiv.org/abs/1705.09355)
10/31 | Two-sample nonparametric testing for random graphs | [Tang et al.](https://arxiv.org/abs/1409.2344), [Gretton et al.](http://jmlr.csail.mit.edu/papers/v13/gretton12a.html)
11/02 | Two-sample nonparametric testing for random graphs (day 2) | [Tang et al.](https://arxiv.org/abs/1409.2344), [Gretton et al.](http://jmlr.csail.mit.edu/papers/v13/gretton12a.html)
11/05 | Universal singula value thresholding | [Chatterjee] (https://arxiv.org/abs/1212.1247), [Xu](https://arxiv.org/abs/1709.03183)
11/07 | Universal singula value thresholding (day 2) | [Chatterjee] (https://arxiv.org/abs/1212.1247), [Xu](https://arxiv.org/abs/1709.03183)
11/09 | Universal singula value thresholding (day 3) | [Chatterjee] (https://arxiv.org/abs/1212.1247), [Xu](https://arxiv.org/abs/1709.03183)
11/12 | Breather day | [The Corrs](https://www.youtube.com/watch?v=vzerbXFwGCE), [Richie Havens](https://www.youtube.com/watch?v=rynxqdNMry4)
11/14 | Exponential random graphs model | [Shalizi and Rinaldo](https://arxiv.org/abs/1111.3054)
11/16 | Goodness-of-fit test in stochastic blockmodels | [Lei](https://arxiv.org/abs/1412.4857), [Wang and Bickel](https://projecteuclid.org/euclid.aos/1494921948)
11/26 | Stochastic blockmodels and limit of detectability | [Mossel et al.](https://arxiv.org/abs/1202.1499), [Abbe et al.](https://arxiv.org/abs/1405.3267), [Hajek et al.](https://arxiv.org/abs/1509.07859), [Abbe](https://arxiv.org/abs/1703.10146)
11/28 | Stochastic blockmodels and limit of detectability (day 2) | [Mossel et al.](https://arxiv.org/abs/1202.1499), [Abbe et al.](https://arxiv.org/abs/1405.3267), [Hajek et al.](https://arxiv.org/abs/1509.07859), [Abbe](https://arxiv.org/abs/1703.10146)
11/30 | Stochastic blockmodels and limit of detectability (day 3) | [Mossel et al.](https://arxiv.org/abs/1202.1499), [Abbe et al.](https://arxiv.org/abs/1405.3267), [Hajek et al.](https://arxiv.org/abs/1509.07859), [Abbe](https://arxiv.org/abs/1703.10146)
12/03 | All Caratheodory, all the time | [Staying alive](https://www.youtube.com/watch?v=5WXVaChA3Q0)
12/05 | Dynkin-Dynkin | [Hey](https://www.youtube.com/watch?v=ggUkKaKFv7I)
12/07 | Proof of the Riemann hypothesis using elementary linear algebra | [Moskau](https://www.youtube.com/watch?v=paiQRSpg4Aw)




