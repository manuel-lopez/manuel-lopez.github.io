---
layout: page
title: My thesis topic
permalink: /thesis/
---

<html > 
<head><title>Linear and Non-linear Non-negative Decomposition for the Analysis of Multi-source/Multi-parameter Ocean
Dynamics Datasets</title> 
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1"> 
<meta name="generator" content="TeX4ht (http://www.cse.ohio-state.edu/~gurari/TeX4ht/)"> 
<meta name="originator" content="TeX4ht (http://www.cse.ohio-state.edu/~gurari/TeX4ht/)"> 
<!-- html --> 
<meta name="src" content="main.tex"> 
<meta name="date" content="2017-07-11 10:51:00"> 
<link rel="stylesheet" type="text/css" href="main.css"> 
</head><body 
>
   <div class="maketitle">
                                                                                       
                                                                                       
                                                                                       
                                                                                       

<h2 class="titleHead">Linear and Non-linear Non-negative Decomposition for the
Analysis of Multi-source/Multi-parameter Ocean Dynamics
Datasets</h2>
<div class="author" ><span 
class="ecrm-1200">Manuel LOPEZ RADCENCO</span></div><br />
<div class="date" ></div>
   </div>
   <h3 class="likesectionHead"><a 
 id="x1-1000"></a>Thesis topic</h3>
<!--l. 39--><p class="noindent" >
   <h4 class="likesubsectionHead"><a 
 id="x1-2000"></a>Context and objectives</h4>
<!--l. 40--><p class="noindent" >In the last few years, satellite remote sensing has produced vast amounts of observation data from a wide variety
of sources. A vast array of different sensor types allows for the observation of different terrestrial, oceanic and
atmospheric geophysical and geobiochemical parameters at different spatio-temporal resolutions, which amounts
to a huge quantity of greatly under-exploited data. In this regard, huge exploitation potential exists within these
datasets, particularly for data mining and machine learning approaches, which have proved to be useful for a
wide variety of applications, ranging from high-resolution reconstruction to the spatio-temporal
analysis and segmentation of system dynamics. To fully exploit this potential, however, a better
understanding, representation and modeling of the interactions between interest variables and the
processes behind these interactions is needed. Improved comprehension of variable relationships
would lead to improved quality, power and accuracy of geophysical and geobiochemical process
models and representations, by tackling shortcomings associated both with the available datasets
and with current models and representations. In this context, this thesis project has two major
objectives:
     <ol  class="enumerate1" >
     <li 
  class="enumerate" id="x1-2002x1">Explore non-negative and sparse formulations (cf. [<a 
href="#Xfevotte">8</a>,&#x00A0;<a 
href="#Xparts">19</a>,&#x00A0;<a 
href="#Xozerov">21</a>,&#x00A0;<a 
href="#Xsparse">27</a>]) to develop new unsupervised
     methods to characterize variable relationships from a representative set of observations.
     </li>
     <li 
  class="enumerate" id="x1-2004x2">Exploit the developed methods and formulations to develop new approaches for a wide range of
     multi-source/multi-parameter ocean remote sensing problems and applications.</li></ol>
<!--l. 61--><p class="noindent" >
   <h4 class="likesubsectionHead"><a 
 id="x1-3000"></a>Scientific content</h4>
<!--l. 62--><p class="noindent" >Variable relationship characterization is a classical problem in signal and image processing, for which several
approaches have been proposed (cf. [<a 
href="#Xlatent">6</a>,&#x00A0;<a 
href="#XBSS">22</a>,&#x00A0;<a 
href="#Xtandeo">28</a>]). From a methodological point of view, we aim at
identifying linear or non-linear transfer function dictionaries capable of accurately summarizing and
representing the relationship between two interest variables. To do so, we will exploit non-negative
and sparse decomposition formulations for source separation. From a mathematical point of view,
the classical blind source separation problem (cf. [<a 
href="#XBSS">22</a>]) is generally stated as the observation-based
decomposition of a signal or image <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub> into <span 
class="cmmi-10">K </span>additive components associated with different processes or
sources:
                                                                                       
                                                                                       
   <table 
class="equation"><tr><td><a 
 id="x1-3001r1"></a>
   <center class="math-display" >
<img 
src="main0x.png" alt="      K
yn = &#x2211;  &#x03B1;nkbk +&#x03C9;n
     k=1
" class="math-display" ></center></td><td class="equation-label">          (1)</td></tr></table>
<!--l. 69--><p class="nopar" ><br>
where <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup>, coefficient <span 
class="cmmi-10">&#x03B1;</span><sub><span 
class="cmmi-7">nk</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D; </span>quantifies the contribution of component <span 
class="cmmib-10">b</span><sub><span 
class="cmmi-7">k</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup>, which corresponds to the
<span 
class="cmmi-10">k</span>-th reference signal or image and <span 
class="cmmib-10">&#x03C9;</span><sub><span 
class="cmmi-7">n</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup> is a multivariate white Gaussian noise process.<br 
class="newline" />In this context, non-negative and sparse formulations (cf. [<a 
href="#Xfevotte">8</a>,&#x00A0;<a 
href="#Xparts">19</a>,&#x00A0;<a 
href="#Xozerov">21</a>,&#x00A0;<a 
href="#Xsparse">27</a>]) will constraint the problem to allow
for the development of more suitable models and to ensure the identifiability of the model from a set of
observations of signals or images <span 
class="cmsy-10">{</span><span 
class="cmbx-10">y</span><span 
class="cmsy-10">}</span><sub><span 
class="cmmi-7">n</span></sub>. <br 
class="newline" />Our objective is to extend model (<a 
href="#x1-3001r1">1<!--tex4ht:ref: eq:base --></a>), and its non-negative/sparse constrained variants, to the identification and
separation of linear or non-linear relationships between two variables <span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub> and <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub> from a representative set of joint
observations <span 
class="cmsy-10">{</span><span 
class="cmbx-10">x</span><span 
class="cmmi-10">,</span><span 
class="cmbx-10">y</span><span 
class="cmsy-10">}</span><sub><span 
class="cmmi-7">n</span></sub>. The core hypothesis here lies in the validity of the following model:
   <table 
class="equation"><tr><td><a 
 id="x1-3002r2"></a>
   <center class="math-display" >
<img 
src="main1x.png" alt="     &#x2211;K
yn =    &#x03B1;nkf&#x03B8;k(xn )+ &#x03C9;n
     k=1
" class="math-display" ></center></td><td class="equation-label">           (2)</td></tr></table>
<!--l. 77--><p class="nopar" >
<!--l. 79--><p class="indent" > <br>
where <span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">J</span></sup>, <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup>, coefficient <span 
class="cmmi-10">&#x03B1;</span><sub><span 
class="cmmi-7">nk</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D; </span>quantifies the amplitude of the relationship <span 
class="cmmi-10">f</span><sub><span 
class="cmmi-7">&#x03B8;</span><sub><span 
class="cmmi-5">k</span></sub></sub><span 
class="cmr-10">(</span><span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub><span 
class="cmr-10">) </span><span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup> for
observations <span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub> and <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub>, which corresponds to the <span 
class="cmmi-10">k</span>-th element of the linear or non-linear transfer
function dictionary, and <span 
class="cmmib-10">&#x03C9;</span><sub><span 
class="cmmi-7">n</span></sub> <span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmmi-7">I</span></sup> is a multivariate random noise process that characterizes global
incertitude.<br 
class="newline" />Each transfer function <span 
class="cmmi-10">f</span><sub><span 
class="cmmi-7">&#x03B8;</span><sub><span 
class="cmmi-5">k</span></sub></sub> is characterized by a set of parameters <span 
class="cmmi-10">&#x03B8;</span><sub><span 
class="cmmi-7">k</span></sub>, which we aim to identify along with the
mixing coefficients <span 
class="cmmi-10">&#x03B1;</span><sub><span 
class="cmmi-7">nk</span></sub>.<br 
class="newline" />
<!--l. 91--><p class="indent" >   With respect to model (<a 
href="#x1-3002r2">2<!--tex4ht:ref: eq:general --></a>), our main objectives are:
     <ul class="itemize1">
     <li class="itemize">Determine the conditions under which the model is identifiable from a set of joint observations.
     </li>
     <li class="itemize">Develop efficient algorithms for model characterization and ensure their viability for cases where
     massive multi-dimensional datasets are involved.
     </li>
     <li class="itemize">Apply the proposed model for the characterization of both dynamical system models and observation
     models.
     </li>
     <li class="itemize">Apply the proposed model and algorithms to relevant ocean remote sensing problems.</li></ul>
                                                                                       
                                                                                       
<!--l. 99--><p class="noindent" >
   <h3 class="likesectionHead"><a 
 id="x1-4000"></a>State of the art and thesis topic position</h3>
<!--l. 101--><p class="noindent" >
   <h4 class="likesubsectionHead"><a 
 id="x1-5000"></a>Motivation and previous work in physical oceanography</h4>
<!--l. 102--><p class="noindent" >As previously stated, the amount of multi-source ocean remote sensing data available has experienced
considerable growth in the last few decades, which has been a key factor for more thorough analysis possibilities
leading to a better understanding of upper ocean dynamics, ocean circulation and atmosphere-ocean
interactions.<br 
class="newline" />In particular, a considerable amount of effort has been put into understanding the relationships and interactions
between different oceanic physical quantities (cf. [<a 
href="#Xmethods_1">3</a>,&#x00A0;<a 
href="#Xcasey">4</a>,&#x00A0;<a 
href="#XSST_SSH_1">10</a>,&#x00A0;<a 
href="#Xisern">12</a>,&#x00A0;<a 
href="#Xleuliette">20</a>,&#x00A0;<a 
href="#Xsaraceno">26</a>]). In [<a 
href="#Xtandeo">28</a>], the authors show that
surface currents can be directly retrieved from SSH (Sea Surface Height) fields using the geostrophy
balance. Additionally, the existence of a sea surface dynamical mode, referred to as the SQG mode
(Surface Quasi-Geostrophy), characterized by a linear transfer function between ST (Sea Surface
Temperature) and SSH, has been exhibited both from theoretical and observation-driven studies
(cf. [<a 
href="#XSST_SSH_1">10</a>,&#x00A0;<a 
href="#XHeld">11</a>,&#x00A0;<a 
href="#XSST_SSH_2">13</a>,&#x00A0;<a 
href="#XKlein">15</a>,&#x00A0;<a 
href="#XSST_SSH_3">16</a>,&#x00A0;<a 
href="#XSST_SSH_4">17</a>,&#x00A0;<a 
href="#XLapeyre">18</a>,&#x00A0;<a 
href="#Xtandeo">28</a>]). Indeed, recent work points out that upper ocean dynamics
may be characterized by local SSH-SST linear relationships that correspond precisely to fractional
Laplacian operators (cf. [<a 
href="#XSST_SSH_1">10</a>,&#x00A0;<a 
href="#XSST_SSH_2">13</a>,&#x00A0;<a 
href="#XSST_SSH_3">16</a>,&#x00A0;<a 
href="#XSST_SSH_4">17</a>,&#x00A0;<a 
href="#XLapeyre">18</a>,&#x00A0;<a 
href="#Xtandeo">28</a>]), and uses this characterization to draw the following
conclusions:
     <ul class="itemize1">
     <li class="itemize">Surface currents, given as the orthogonal gradient of the SSH, can be derived as spatial derivatives
     of a filtered version of the SST (cf. [<a 
href="#Xisern">12</a>,&#x00A0;<a 
href="#Xtandeo">28</a>]);
     </li>
     <li class="itemize">A single linear transfer function may not be enough to capture the high complexity of upper ocean
     dynamics, since the SQG relationship assumes specific vertical mixing conditions that may not be
     valid anywhere or at any time (cf. [<a 
href="#XCristina">9</a>,&#x00A0;<a 
href="#Xisern_fontanet">14</a>,&#x00A0;<a 
href="#XLapeyre">18</a>]).</li></ul>
<!--l. 119--><p class="indent" >   These findings motivated the development of new statistical observation-driven methods to combine available
SSH information with other remote sensing data, such as microwave SST, or <span 
class="ecti-1000">in situ </span>data (cf. [<a 
href="#Xmethods_1">3</a>,&#x00A0;<a 
href="#Xmethods_2">5</a>,&#x00A0;<a 
href="#Xtandeo">28</a>,&#x00A0;<a 
href="#Xmethods_3">30</a>]).
Whereas [<a 
href="#XCristina">9</a>,&#x00A0;<a 
href="#Xisern_fontanet">14</a>] investigated Fourier-based representations of linear SSH-SST couplings, Tandeo et al. (cf. [<a 
href="#Xtandeo">28</a>])
hypothesize that upper ocean dynamics may be predicted from surface density horizontal variations possibly
dominated by SST fields. They exploit this idea to explore linear transfer functions between SSH and SST by
introducing a multi-modal decomposition, using a latent class regression model, such that local
SSH-SST relationships are described by one among a predefined number of possible linear transfer
functions.<br 
class="newline" />An important limitation of latent class regression models is that they can only account for a finite set of linear
transfer functions. By contrast, the SQG mode is characterized by a single class of linear transfer functions,
namely the fractional Laplacian operator <span 
class="cmmi-10">&#x03B3;</span><span 
class="cmr-10">&#x0394;</span><sup><span 
class="cmr-7">1</span><span 
class="cmmi-7">&#x2215;</span><span 
class="cmr-7">2</span></sup>, but involves a free positive scalar parameter <span 
class="cmmi-10">&#x03B3; </span>(cf.
[<a 
href="#XHeld">11</a>,&#x00A0;<a 
href="#XLapeyre">18</a>,&#x00A0;<a 
href="#Xtandeo">28</a>]), which relates to local geophysical features (e.g., mixed layer depth). As a result,
SQG-like upper ocean dynamics, characterized by continuously-varying <span 
class="cmmi-10">&#x03B3; </span>parameters, may not be well
represented by latent class regression models. Such considerations lead us to consider a non-negative
linear version of model (<a 
href="#x1-3002r2">2<!--tex4ht:ref: eq:general --></a>) (linear transfer functions <span 
class="cmmi-10">f</span><sub><span 
class="cmmi-7">&#x03B8;</span><sub><span 
class="cmmi-5">k</span></sub></sub>, non-negative mixing coefficients <span 
class="cmmi-10">&#x03B1;</span><sub><span 
class="cmmi-7">nk</span></sub>),
where the relationship between SST and SSH is a non-negative linear combination of <span 
class="cmmi-10">K </span>linear
regressions. An observation-wise adjustable amplitude parameter <span 
class="cmmi-10">&#x03B1; </span><span 
class="cmsy-10">&#x2208; </span><span 
class="msbm-10">&#x211D;</span><sup><span 
class="cmr-7">+</span></sup> is used to take into account
local variations in the strength of the relationships, in a manner similar to coefficient <span 
class="cmmi-10">&#x03B3; </span>in SQG
dynamics.<br 
class="newline" />It should be noted that the considered non-negative decomposition suggests that the dynamical modes in play do
not exclude each other but are rather superimposed. This is significantly different from the basis assumption
made by the latent class regression model developed in [<a 
href="#Xtandeo">28</a>], which assumes that only one mode is active at any
space-time location. Whereas previous works focused either on spatially homogeneous linear SSH-SST couplings
(cf. [<a 
href="#XCristina">9</a>,&#x00A0;<a 
href="#Xisern_fontanet">14</a>]) or on a finite set of linear SSH-SST transfer functions (cf. [<a 
href="#Xtandeo">28</a>]), we consider here a richer
representation, accounting for all mixing possibilities between a finite set of families of linear SSH-SST
relationships.<br 
class="newline" />To our knowledge, this thesis topic is the first study to exhibit, from an observation-driven analysis, the
continuous superimposition of different dynamical modes associated with different types of SSH-SST
transfer functions. We further stress that multi-modal approaches are necessary, as a single linear
transfer function does not suffice to capture the complex non-stationary space-time variability of
                                                                                       
                                                                                       
mesoscale upper ocean dynamics. Previous work rather explored regional mean transfer functions (cf.
[<a 
href="#XCristina">9</a>,&#x00A0;<a 
href="#Xisern_fontanet">14</a>]) or latent class mixture models (cf. [<a 
href="#Xtandeo">28</a>]), even though obtained results truly support the
existence of superimposed dynamical modes, rather than mutually exclusive ones as assumed in
[<a 
href="#Xtandeo">28</a>].
<!--l. 131--><p class="noindent" >
   <h4 class="likesubsectionHead"><a 
 id="x1-6000"></a>Methodological aspects and previous work in signal and image processing</h4>
<!--l. 132--><p class="noindent" >The separation and identification of contributions associated with different types of sources or processes from
multiple observations is a general problem in signal and image processing (cf. [<a 
href="#XBSS">22</a>]). Significant advances in blind
source separation have been reported in the last decade with the introduction of non-negative and sparse
formulations (cf. [<a 
href="#Xfevotte">8</a>,&#x00A0;<a 
href="#Xparts">19</a>,&#x00A0;<a 
href="#Xozerov">21</a>,&#x00A0;<a 
href="#Xsparse">27</a>]). In the context introduced by the classical blind source separation problem
formulated in (<a 
href="#x1-3001r1">1<!--tex4ht:ref: eq:base --></a>), non-negativity constraints are used to develop part-based representations that have
multiple applications, ranging from learning parts of faces or semantic features of text (cf. [<a 
href="#Xparts">19</a>]) to
audio blind source separation of convolutive mixtures (cf. [<a 
href="#Xfevotte">8</a>]). Sparsity constraints, on the other
hand, allow for dimensionality reduction and simpler representations of high-dimensional data (cf.
[<a 
href="#Xlasso">29</a>]), thus leading to the development of simpler models and representations that are easier to
understand.<br 
class="newline" />Inspired by latent class regression models (cf. [<a 
href="#Xlatent">6</a>]) applications to satellite-derived remote sensing oceanic data,
as in [<a 
href="#Xtandeo">28</a>], we introduce a non-negative linear version of model (<a 
href="#x1-3002r2">2<!--tex4ht:ref: eq:general --></a>) (linear transfer functions <span 
class="cmmi-10">f</span><sub><span 
class="cmmi-7">&#x03B8;</span><sub><span 
class="cmmi-5">k</span></sub></sub>, non-negative
mixing coefficients <span 
class="cmmi-10">&#x03B1;</span><sub><span 
class="cmmi-7">nk</span></sub>), and develop algorithms for model parameter estimation. Such a model allows us to
address decomposition problems involving mixed linear contributions, thus generalizing linear mixture problems
involving linear regressions and latent class regression models. In particular, the non-negativity constraint
provides the mean for distinguishing the form of the linear relationships between variables <span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub> and <span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub> from the
magnitude of these relationships.<br 
class="newline" />Compared to state-of-the-art models like classical regression and latent class regression models, the key features
of the proposed model are two-fold: first, it accounts for possibly varying magnitudes of the linear relationships;
second, it explicitly evaluates the relative importance of different linear relationships. This is of wide
interest for a variety applications such as transfer function identification, regime-switching dynamics,
etc.<br 
class="newline" />Following this developments, an alternative reformulation of the problem, based on the estimation of locally
linear operators representing the relationships between each observation pair <span 
class="cmr-10">(</span><span 
class="cmbx-10">x</span><sub><span 
class="cmmi-7">n</span></sub><span 
class="cmmi-10">,</span><span 
class="cmbx-10">y</span><sub><span 
class="cmmi-7">n</span></sub><span 
class="cmr-10">)</span>, and the subsequent
decomposition of such regressions using dictionary learning approaches, is considered. We explore such
formulation to address robustness issues with the original model, and to allow for the seamless integration of
different constraints by selecting appropriate dictionary learning approaches, such as sparsity by means of KSVD
(cf. [<a 
href="#Xaharon">1</a>,&#x00A0;<a 
href="#XRubinstein">24</a>]), which has already been used extensively for a wide variety of applications, including analysis
sparse model learning (cf. [<a 
href="#Xaksvd">23</a>]), transformation learning (cf. [<a 
href="#Xtksvd">7</a>]) and face recognition (cf. [<a 
href="#Xfksvd">31</a>]), and
exists in several variants, including a non-negative variant (cf. [<a 
href="#Xnnksvd">2</a>]) and a double spase variant (cf.
[<a 
href="#Xdouble_sparse">25</a>]).<br 
class="newline" />Finally, even though our original motivation was to overcome some drawbacks of classical models for physical
oceanography applications, the proposed model and algorithms proved to have much greater capabilities.
They constitute, in fact, a general tool for the analysis of variable relationships, i.e., for analyzing
and synthesizing variable correlation. Such a tool would allow for the analysis, segmentation and
reconstruction of the relationship between any two interest variables in any given setting, thus allowing
for a deeper insight into the nature of said relationship and the processes and phenomena behind
it.
<!--l. 162--><p class="noindent" >
   <h3 class="likesectionHead"><a 
 id="x1-7000"></a><span 
class="ecrm-0900">References</span></h3>
<!--l. 2--><p class="noindent" >
   <h3 class="likesectionHead"><a 
 id="x1-8000"></a></h3>
<!--l. 2--><p class="noindent" >
    <div class="thebibliography">
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xaharon"></a><span 
class="ecrm-0900">[1]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">M.</span><span 
class="ecrm-0900">&#x00A0;Aharon, M.</span><span 
class="ecrm-0900">&#x00A0;Elad, and A.</span><span 
class="ecrm-0900">&#x00A0;Bruckstein.  k -svd: An algorithm for designing overcomplete dictionaries</span>
    <span 
class="ecrm-0900">for sparse representation. </span><span 
class="ecti-0900">IEEE Transactions on Signal Processing</span><span 
class="ecrm-0900">, 54(11):4311&#8211;4322, Nov 2006.</span>
                                                                                       
                                                                                       
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xnnksvd"></a><span 
class="ecrm-0900">[2]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">M.</span><span 
class="ecrm-0900">&#x00A0;Aharon, M.</span><span 
class="ecrm-0900">&#x00A0;Elad, and A.</span><span 
class="ecrm-0900">&#x00A0;M. Bruckstein.  K-svd and its non-negative variant for dictionary design.</span>
    <span 
class="ecrm-0900">In </span><span 
class="ecti-0900">Proceedings of the SPIE conference wavelets</span><span 
class="ecrm-0900">, pages 327&#8211;339, 2005.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xmethods_1"></a><span 
class="ecrm-0900">[3]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">M.</span><span 
class="ecrm-0900">&#x00A0;M. Ali, D.</span><span 
class="ecrm-0900">&#x00A0;Swain, and R.</span><span 
class="ecrm-0900">&#x00A0;A. Weller. Estimation of ocean subsurface thermal structure from surface</span>
    <span 
class="ecrm-0900">parameters: A neural network approach. </span><span 
class="ecti-0900">Geophysical Research Letters</span><span 
class="ecrm-0900">, 31(20):n/a&#8211;n/a, 2004. L20308.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xcasey"></a><span 
class="ecrm-0900">[4]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">K.</span><span 
class="ecrm-0900">&#x00A0;S. Casey and D.</span><span 
class="ecrm-0900">&#x00A0;Adamec.  Sea surface temperature and sea surface height variability in the north</span>
    <span 
class="ecrm-0900">pacific ocean from 1993 to 1999. </span><span 
class="ecti-0900">Journal of Geophysical Research: Oceans</span><span 
class="ecrm-0900">, 107(C8):14&#8211;1&#8211;14&#8211;12, 2002.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xmethods_2"></a><span 
class="ecrm-0900">[5]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">P.</span><span 
class="ecrm-0900">&#x00A0;C.  Chu,  C.</span><span 
class="ecrm-0900">&#x00A0;Fan,  and  W.</span><span 
class="ecrm-0900">&#x00A0;T.  Liu.   Determination  of  vertical  thermal  structure  from  sea  surface</span>
    <span 
class="ecrm-0900">temperature. </span><span 
class="ecti-0900">Journal of Atmospheric and Oceanic Technology</span><span 
class="ecrm-0900">, 17(7):971&#8211;979, 2016/01/21 2000.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xlatent"></a><span 
class="ecrm-0900">[6]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">W.</span><span 
class="ecrm-0900">&#x00A0;DeSarbo and W.</span><span 
class="ecrm-0900">&#x00A0;Cron. A maximum likelihood methodology for clusterwise linear regression. </span><span 
class="ecti-0900">Journal</span>
    <span 
class="ecti-0900">of Classification</span><span 
class="ecrm-0900">, 5(2):249&#8211;282, 1988.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xtksvd"></a><span 
class="ecrm-0900">[7]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">E.</span><span 
class="ecrm-0900">&#x00A0;M. Eksioglu and O.</span><span 
class="ecrm-0900">&#x00A0;Bayir. K-svd meets transform learning: Transform k-svd. </span><span 
class="ecti-0900">IEEE Signal Processing</span>
    <span 
class="ecti-0900">Letters</span><span 
class="ecrm-0900">, 21(3):347&#8211;351, March 2014.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="Xfevotte"></a><span 
class="ecrm-0900">[8]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">C.</span><span 
class="ecrm-0900">&#x00A0;F</span><span 
class="ecrm-0900">\E9votte,  N.</span><span 
class="ecrm-0900">&#x00A0;Bertin,  and  J.</span><span 
class="ecrm-0900">&#x00A0;Durrieu.    Nonnegative  matrix  factorization  with  the  itakura-saito</span>
    <span 
class="ecrm-0900">divergence: With application to music analysis. </span><span 
class="ecti-0900">Neural Comput.</span><span 
class="ecrm-0900">, 21(3):793&#8211;830, Mar. 2009.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
 <a 
 id="XCristina"></a><span 
class="ecrm-0900">[9]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">C.</span><span 
class="ecrm-0900">&#x00A0;Gonz</span><span 
class="ecrm-0900">\E1lez-Haro  and  J.</span><span 
class="ecrm-0900">&#x00A0;Isern-Fontanet.   Global  ocean  current  reconstruction  from  altimetric  and</span>
    <span 
class="ecrm-0900">microwave SST measurements. </span><span 
class="ecti-0900">Journal of Geophysical Research: Oceans</span><span 
class="ecrm-0900">, 119(6):3378&#8211;3391, 2014.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XSST_SSH_1"></a><span 
class="ecrm-0900">[10]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">U.</span><span 
class="ecrm-0900">&#x00A0;Hausmann and A.</span><span 
class="ecrm-0900">&#x00A0;Czaja. The observed signature of mesoscale eddies in sea surface temperature and</span>
    <span 
class="ecrm-0900">the associated heat transport. </span><span 
class="ecti-0900">Deep Sea Research Part I: Oceanographic Research Papers</span><span 
class="ecrm-0900">, 70:60 &#8211; 72, 2012.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XHeld"></a><span 
class="ecrm-0900">[11]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">I.</span><span 
class="ecrm-0900">&#x00A0;M. Held, R.</span><span 
class="ecrm-0900">&#x00A0;T. Pierrehumbert, S.</span><span 
class="ecrm-0900">&#x00A0;T. Garner, and K.</span><span 
class="ecrm-0900">&#x00A0;L. Swanson. Surface quasi-geostrophic dynamics.</span>
    <span 
class="ecti-0900">Journal of Fluid Mechanics</span><span 
class="ecrm-0900">, 282:1&#8211;20, 1 1995.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xisern"></a><span 
class="ecrm-0900">[12]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">J.</span><span 
class="ecrm-0900">&#x00A0;Isern-Fontanet,  B.</span><span 
class="ecrm-0900">&#x00A0;Chapron,  G.</span><span 
class="ecrm-0900">&#x00A0;Lapeyre,  and  P.</span><span 
class="ecrm-0900">&#x00A0;Klein.   Potential  use  of  microwave  sea  surface</span>
    <span 
class="ecrm-0900">temperatures for the estimation of ocean currents.   </span><span 
class="ecti-0900">Geophysical Research Letters</span><span 
class="ecrm-0900">, 33(24):n/a&#8211;n/a, 2006.</span>
    <span 
class="ecrm-0900">L24608.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XSST_SSH_2"></a><span 
class="ecrm-0900">[13]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">J.</span><span 
class="ecrm-0900">&#x00A0;Isern-Fontanet,   G.</span><span 
class="ecrm-0900">&#x00A0;Lapeyre,   P.</span><span 
class="ecrm-0900">&#x00A0;Klein,   B.</span><span 
class="ecrm-0900">&#x00A0;Chapron,   and   M.</span><span 
class="ecrm-0900">&#x00A0;W.   Hecht.      Three-dimensional</span>
    <span 
class="ecrm-0900">reconstruction of oceanic mesoscale currents from surface information.  </span><span 
class="ecti-0900">Journal of Geophysical Research:</span>
    <span 
class="ecti-0900">Oceans</span><span 
class="ecrm-0900">, 113(C9):n/a&#8211;n/a, 2008. C09005.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xisern_fontanet"></a><span 
class="ecrm-0900">[14]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">J.</span><span 
class="ecrm-0900">&#x00A0;Isern-Fontanet, M.</span><span 
class="ecrm-0900">&#x00A0;Shinde, and C.</span><span 
class="ecrm-0900">&#x00A0;Gonz</span><span 
class="ecrm-0900">\E1lez-Haro. On the transfer function between surface fields and</span>
    <span 
class="ecrm-0900">the geostrophic stream function in the Mediterranean Sea. </span><span 
class="ecti-0900">Journal of Physical Oceanography</span><span 
class="ecrm-0900">, 44:1406&#8211;1423,</span>
    <span 
class="ecrm-0900">2014.</span>
                                                                                       
                                                                                       
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XKlein"></a><span 
class="ecrm-0900">[15]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">P.</span><span 
class="ecrm-0900">&#x00A0;Klein, B.</span><span 
class="ecrm-0900">&#x00A0;L. Hua, G.</span><span 
class="ecrm-0900">&#x00A0;Lapeyre, X.</span><span 
class="ecrm-0900">&#x00A0;Capet, S.</span><span 
class="ecrm-0900">&#x00A0;Le Gentil, and H.</span><span 
class="ecrm-0900">&#x00A0;Sasaki. Upper ocean turbulence from</span>
    <span 
class="ecrm-0900">high 3-D resolution simulations. </span><span 
class="ecti-0900">Journal of Physical Oceanography</span><span 
class="ecrm-0900">, 38:1748&#8211;1763, 2008.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XSST_SSH_3"></a><span 
class="ecrm-0900">[16]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">P.</span><span 
class="ecrm-0900">&#x00A0;Klein,  J.</span><span 
class="ecrm-0900">&#x00A0;Isern-Fontanet,  G.</span><span 
class="ecrm-0900">&#x00A0;Lapeyre,  G.</span><span 
class="ecrm-0900">&#x00A0;Roullet,  E.</span><span 
class="ecrm-0900">&#x00A0;Danioux,  B.</span><span 
class="ecrm-0900">&#x00A0;Chapron,  S.</span><span 
class="ecrm-0900">&#x00A0;Le</span><span 
class="ecrm-0900">&#x00A0;Gentil,  and</span>
    <span 
class="ecrm-0900">H.</span><span 
class="ecrm-0900">&#x00A0;Sasaki.   Diagnosis  of  vertical  velocities  in  the  upper  ocean  from  high  resolution  sea  surface  height.</span>
    <span 
class="ecti-0900">Geophysical Research Letters</span><span 
class="ecrm-0900">, 36(12):n/a&#8211;n/a, 2009. L12603.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XSST_SSH_4"></a><span 
class="ecrm-0900">[17]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">J.</span><span 
class="ecrm-0900">&#x00A0;H.  LaCasce  and  A.</span><span 
class="ecrm-0900">&#x00A0;Mahadevan.    Estimating  subsurface  horizontal  and  vertical  velocities  from</span>
    <span 
class="ecrm-0900">sea-surface temperature. </span><span 
class="ecti-0900">Journal of Marine Research</span><span 
class="ecrm-0900">, 64(5):695&#8211;721, 2006-09-01T00:00:00.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XLapeyre"></a><span 
class="ecrm-0900">[18]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">G.</span><span 
class="ecrm-0900">&#x00A0;Lapeyre and P.</span><span 
class="ecrm-0900">&#x00A0;Klein.  Dynamics of the upper oceanic layers in terms of surface quasigeostrophy</span>
    <span 
class="ecrm-0900">theory. </span><span 
class="ecti-0900">Journal of Physical Oceanography</span><span 
class="ecrm-0900">, 36:165&#8211;176, 2006.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xparts"></a><span 
class="ecrm-0900">[19]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">D.</span><span 
class="ecrm-0900">&#x00A0;Lee and H.</span><span 
class="ecrm-0900">&#x00A0;Seung.   Learning the parts of objects by non-negative matrix factorization.   </span><span 
class="ecti-0900">Nature</span><span 
class="ecrm-0900">,</span>
    <span 
class="ecrm-0900">401(6755):788&#8211;791, Oct. 1999.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xleuliette"></a><span 
class="ecrm-0900">[20]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">E.</span><span 
class="ecrm-0900">&#x00A0;W.  Leuliette  and  J.</span><span 
class="ecrm-0900">&#x00A0;M.  Wahr.     Coupled  pattern  analysis  of  sea  surface  temperature  and</span>
    <span 
class="ecrm-0900">TOPEX/Poseidon sea surface height. </span><span 
class="ecti-0900">Journal of Physical Oceanography</span><span 
class="ecrm-0900">, 29(4):599&#8211;611, 2016/01/22 1999.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xozerov"></a><span 
class="ecrm-0900">[21]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">A.</span><span 
class="ecrm-0900">&#x00A0;Ozerov and C.</span><span 
class="ecrm-0900">&#x00A0;Fevotte.  Multichannel nonnegative matrix factorization in convolutive mixtures for</span>
    <span 
class="ecrm-0900">audio source separation.  </span><span 
class="ecti-0900">Audio, Speech, and Language Processing, IEEE Transactions on</span><span 
class="ecrm-0900">, 18(3):550&#8211;563,</span>
    <span 
class="ecrm-0900">March 2010.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XBSS"></a><span 
class="ecrm-0900">[22]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">M.</span><span 
class="ecrm-0900">&#x00A0;Pal,  R.</span><span 
class="ecrm-0900">&#x00A0;Roy,  J.</span><span 
class="ecrm-0900">&#x00A0;Basu,  and  M.</span><span 
class="ecrm-0900">&#x00A0;Bepari.    Blind  source  separation:  A  review  and  analysis.    In</span>
    <span 
class="ecti-0900">Oriental COCOSDA held jointly with 2013 Conference on Asian Spoken Language Research and Evaluation</span>
    <span 
class="ecti-0900">(O-COCOSDA/CASLRE), 2013 International Conference</span><span 
class="ecrm-0900">, pages 1&#8211;5, Nov 2013.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xaksvd"></a><span 
class="ecrm-0900">[23]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">R.</span><span 
class="ecrm-0900">&#x00A0;Rubinstein, T.</span><span 
class="ecrm-0900">&#x00A0;Peleg, and M.</span><span 
class="ecrm-0900">&#x00A0;Elad. Analysis k-svd: A dictionary-learning algorithm for the analysis</span>
    <span 
class="ecrm-0900">sparse model. </span><span 
class="ecti-0900">IEEE Transactions on Signal Processing</span><span 
class="ecrm-0900">, 61(3):661&#8211;677, Feb 2013.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="XRubinstein"></a><span 
class="ecrm-0900">[24]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">R.</span><span 
class="ecrm-0900">&#x00A0;Rubinstein, M.</span><span 
class="ecrm-0900">&#x00A0;Zibulevsky, and M.</span><span 
class="ecrm-0900">&#x00A0;Elad. Efficient implementation of the k-svd algorithm using batch</span>
    <span 
class="ecrm-0900">orthogonal matching pursuit.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdouble_sparse"></a><span 
class="ecrm-0900">[25]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">R.</span><span 
class="ecrm-0900">&#x00A0;Rubinstein, M.</span><span 
class="ecrm-0900">&#x00A0;Zibulevsky, and M.</span><span 
class="ecrm-0900">&#x00A0;Elad.  Double sparsity: Learning sparse dictionaries for sparse</span>
    <span 
class="ecrm-0900">signal approximation. </span><span 
class="ecti-0900">IEEE Transactions on Signal Processing</span><span 
class="ecrm-0900">, 58(3):1553&#8211;1564, March 2010.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsaraceno"></a><span 
class="ecrm-0900">[26]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">M.</span><span 
class="ecrm-0900">&#x00A0;Saraceno,  C.</span><span 
class="ecrm-0900">&#x00A0;Provost,  and  A.</span><span 
class="ecrm-0900">&#x00A0;R.  Piola.   On  the  relationship  between  satellite-retrieved  surface</span>
    <span 
class="ecrm-0900">temperature fronts and chlorophyll a in the western south atlantic. </span><span 
class="ecti-0900">Journal of Geophysical Research: Oceans</span><span 
class="ecrm-0900">,</span>
    <span 
class="ecrm-0900">110(C11):n/a&#8211;n/a, 2005. C11016.</span>
    </p>
                                                                                       
                                                                                       
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsparse"></a><span 
class="ecrm-0900">[27]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">K.</span><span 
class="ecrm-0900">&#x00A0;Stadlthanner,  F.</span><span 
class="ecrm-0900">&#x00A0;Theis,  C.</span><span 
class="ecrm-0900">&#x00A0;Puntonet,  and  E.</span><span 
class="ecrm-0900">&#x00A0;Lang.      Extended  sparse  nonnegative  matrix</span>
    <span 
class="ecrm-0900">factorization.    In  J.</span><span 
class="ecrm-0900">&#x00A0;Cabestany,  A.</span><span 
class="ecrm-0900">&#x00A0;Prieto,  and  F.</span><span 
class="ecrm-0900">&#x00A0;Sandoval,  editors,  </span><span 
class="ecti-0900">Computational  Intelligence  and</span>
    <span 
class="ecti-0900">Bioinspired Systems</span><span 
class="ecrm-0900">, volume 3512 of </span><span 
class="ecti-0900">Lecture Notes in Computer Science</span><span 
class="ecrm-0900">, pages 249&#8211;256. Springer Berlin</span>
    <span 
class="ecrm-0900">Heidelberg, 2005.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtandeo"></a><span 
class="ecrm-0900">[28]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">P.</span><span 
class="ecrm-0900">&#x00A0;Tandeo, B.</span><span 
class="ecrm-0900">&#x00A0;Chapron, S.</span><span 
class="ecrm-0900">&#x00A0;Ba, E.</span><span 
class="ecrm-0900">&#x00A0;Autret, and R.</span><span 
class="ecrm-0900">&#x00A0;Fablet.  Segmentation of mesoscale ocean surface</span>
    <span 
class="ecrm-0900">dynamics using satellite SST and SSH observations.  </span><span 
class="ecti-0900">Geoscience and Remote Sensing, IEEE Transactions</span>
    <span 
class="ecti-0900">on</span><span 
class="ecrm-0900">, 52(7):4227&#8211;4235, July 2014.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlasso"></a><span 
class="ecrm-0900">[29]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">R.</span><span 
class="ecrm-0900">&#x00A0;Tibshirani. Regression shrinkage and selection via the lasso. </span><span 
class="ecti-0900">Journal of the Royal Statistical Society,</span>
    <span 
class="ecti-0900">Series B</span><span 
class="ecrm-0900">, 58:267&#8211;288, 1994.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmethods_3"></a><span 
class="ecrm-0900">[30]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">X.</span><span 
class="ecrm-0900">&#x00A0;Wu, X.-H. Yan, Y.-H. Jo, and W.</span><span 
class="ecrm-0900">&#x00A0;T. Liu.  Estimation of subsurface temperature anomaly in the</span>
    <span 
class="ecrm-0900">north atlantic using a self-organizing map neural network. </span><span 
class="ecti-0900">Journal of Atmospheric and Oceanic Technology</span><span 
class="ecrm-0900">,</span>
    <span 
class="ecrm-0900">29(11):1675&#8211;1688, 2016/01/21 2012.</span>
    </p>
    <p class="bibitem" ><span class="biblabel">
<a 
 id="Xfksvd"></a><span 
class="ecrm-0900">[31]</span> <span class="bibsp"><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span><span 
class="ecrm-0900">&#x00A0;</span></span></span><span 
class="ecrm-0900">Q.</span><span 
class="ecrm-0900">&#x00A0;Zhang and B.</span><span 
class="ecrm-0900">&#x00A0;Li. Discriminative k-svd for dictionary learning in face recognition. In </span><span 
class="ecti-0900">Computer Vision</span>
    <span 
class="ecti-0900">and Pattern Recognition (CVPR), 2010 IEEE Conference on</span><span 
class="ecrm-0900">, pages 2691&#8211;2698, June 2010.</span>
</p>
    </div>
    
</body></html> 

                                                                                       


