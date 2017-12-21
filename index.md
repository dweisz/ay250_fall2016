### Astronomy 250: Stellar Populations, Fall 2016

**Class Description:**

This class is a survey of contemporary extragalactic stellar populations. We will cover such topics as the IMF, ages of stars and galaxies, dust, modeling resolved and unresolved stellar systems, and interpreting observations of galaxies at various redshifts. This class involves reading and discussion of key current and historical papers, and gaining an appreciation for challenges in the field through select coding exercises and problem sets.

**Instructor:** [Dan Weisz](http://dweisz.github.io), Professor of [Astronomy](www.astro.berkeley.edu)

**Time and Place:** Monday and Wednesday, 10-11:30am in 501b Campbell.

**Office Hours:** Campbell 311. Wednesdays 1:30-2:30pm, by appointment ([email me](mailto:dan.weisz@berkeley.edu)), or anytime I'm in my office and not with anyone else.

**Class Goals:**  

1.  An understanding of stellar populations and how we know ages, metallicities, dust content, etc. for stellar systems (mainly galaxies) in the local and distant Universe.
2.  A basic working knowledge of fitting models to data in a probabilistic framework.
3.  An increased comfort level with working in an open-source environment.

**Format:** Very informal -- Mostly discussion of readings, coding as problem sets, and some lecture.

**Requirements:** 

1. Complete assigned readings
2. Active participation in discussion of papers, including leading of discussion.
3. Make a reasonable attempt at completing the problem sets.
4. *Maybe* pushing a unit test to python FSPS as a final project.

This course requires the use of python and github for problem sets.  More details at the bottom.

#### Course Outline and Topics:

* Intro to Probability, Statistics, and Modeling data (~2 weeks)
* Stellar Initial Mass Function (~2 weeks)
* Resolved Stellar Populations and Stellar Models (~3-4 weeks)
* Dust (~2 weeks)
* Unresolved galaxies near and far (~2 weeks)
* high-z Universe (~2 weeks)

#### Schedule and Assignments:

**0. Intro to Stellar Populations** (Weds 8/24)
 * Assignment due by 8/29: Create a github repo and email me your username.  Install python and jupyter (see below).
 * Excellent overview of Stellar Populations: [Conroy 2013](http://adsabs.harvard.edu/abs/2013ARA%26A..51..393C). A detailed read is not necessary now, but we'll refer to this a lot throughout the semester.
 
**1. Probability, Statistics, and Modeling** (~8/24 - 9/12)
  
* **Topics covered:** Basic probability philosophy & theory, Bayes's theorem, fitting models to data in a probabilistic framework, MCMC sampling techniques, reporting probabilistic output

* **Reading and Resources:**
  * [Brewer](https://github.com/dweisz/ay250_fall2016/blob/master/reading/probstats/brewer_stats331.pdf) Chapters 2-8, Appendix A
  * [Hogg et al.(2012)](http://arxiv.org/abs/1205.4446)
  * [Hogg et al. (2010)](http://arxiv.org/abs/1008.4686) Chapters 1,2,4
  * [Hogg & Foreman-Mackey (in prep)](https://github.com/dweisz/ay250_fall2016/blob/master/reading/probstats/mcmc.pdf)
  * [Foreman-Mackey et al. (2013)](http://arxiv.org/abs/1202.3665)

* **Slides and Notes:**  
 * [8/24](https://github.com/dweisz/ay250_fall2016/tree/master/slides/8:24)
 * [8/29](https://github.com/dweisz/ay250_fall2016/tree/master/slides/8:29)
 * [8/30](https://github.com/dweisz/ay250_fall2016/tree/master/slides/8:30)
 * [9/7](https://github.com/dweisz/ay250_fall2016/tree/master/slides/9:7)
 * [jupyter notebook](https://github.com/dweisz/ay250_fall2016/blob/master/notebooks/2d%20Gaussian%20sampling.ipynb) on sampling from a 2D Gaussian

* [Problem set #1](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps1.pdf) (assigned 8/29, due 9/12)


**2. Stellar IMF** (~9/12 - 9/26)

* **Topics covered:**  What is the IMF, where did it come from, and why is it important?, How to measure the IMF, Historical measurements of the IMF, Current state of the high and low-mass IMF 

* **Class Presentations:**
  * **M 9/12** IMF background, [Salpeter (1955)](http://adsabs.harvard.edu/abs/1955ApJ...121..161S), [Salpeter (2005)](https://github.com/dweisz/ay250_fall2016/blob/master/reading/imf/salpeter2005.pdf) -- Dan
  
  * **W 9/14**
   * (1) IMF Background/History: [Miller & Scalo (1979)](http://adsabs.harvard.edu/abs/1979ApJS...41..513M) -- **Deepthi** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/MillerScalo79_deepthi.pdf))
   * (2) IMF Background/History: [Scalo (1986)](https://github.com/dweisz/ay250_fall2016/blob/master/reading/imf/Scalo1986.IMF.FundCosPhys.pdf) -- **Ned** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/Scalo86_Ned.pdf))

 * **M 9/19**
  * (1) Low-Mass IMF in the MW: [Kroupa(1993)](http://adsabs.harvard.edu/abs/1993MNRAS.262..545K), [Chabrier (2001)](http://arxiv.org/abs/astro-ph/0107018) -- **David**
  * (2) Low-Mass IMF in the MW: [Bochanski (2010)](http://arxiv.org/abs/1004.4002) -- **Saundra** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/stellar_pops_bochanski_saundra.pdf))
  * (3) Low-mass IMF in the Local Group: [Wyse et al. (2002)](http://adsabs.harvard.edu/abs/2002NewA....7..395W), [Geha et al. (2013)](http://adsabs.harvard.edu/abs/2013ApJ...771...29G) -- **Max** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/WyseGehaPresentation_max.pdf))

 * **W 9/21**
  * (1) High-Mass IMF: [Massey et al. (1995b)](http://adsabs.harvard.edu/abs/1995ApJ...454..151M), [Massey (1998)](http://adsabs.harvard.edu/abs/1998ASPC..142...17M), [Massey (2011)](http://adsabs.harvard.edu/abs/2011ASPC..440...29M) -- **Michael** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/Massey_slides_medford.pdf))
  * (2) High-Mass IMF: [Scalo (1998)](http://adsabs.harvard.edu/abs/1998ASPC..142..201S), [Scalo (2005)](http://adsabs.harvard.edu/abs/2005ASSL..327...23S) -- **Irina** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/ScaloReviews_irina.pdf))
  * (3) High-Mass IMF: [Kroupa (2001)](http://adsabs.harvard.edu/abs/2001MNRAS.322..231K), [Weisz et al. (2015)](http://adsabs.harvard.edu/abs/2015ApJ...806..198W) -- **Dan**

 * **M 9/26**
  * (1) Low-mass IMF variations from Integrated Light: [Conroy & van Dokkum (2012)](http://adsabs.harvard.edu/abs/2012ApJ...760...71C), [McConnell et al. (2016)](http://adsabs.harvard.edu/abs/2016ApJ...821...39M) -- **Kareem** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/Low_Mass_IMF_from_Integrated_Light_kareem.pdf))
  * (2) High-Mass IMF variations from Integrated Light: [Lee et al. (2009)](http://adsabs.harvard.edu/abs/2009ApJ...706..599L), [Fumagalli et al. (2011)](http://adsabs.harvard.edu/abs/2011ApJ...741L..26F) -- **Siayo** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/imf/sum_Lee_Fumagalli_pre.pdf))



* [Problem set #2](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps2.pdf) (assigned 9/12, due 9/26)


**3. Resolved Stellar Populations** (~9/28 - 10/17)

* **Topics covered:**  Globular Cluster ages and cosmology, Multiple populations in Globular Clusters, Are clusters really simple stellar populations?, The Local Group, Dwarf Galaxies, Star Formation Histories

* **Class Presentations:**

  * **9/28**  Stellar Evolution Overview -- **Dan**

  * **M 10/3** 
   * (1) Globular Cluster Age Dating: [Chaboyer (2001)](http://adsabs.harvard.edu/abs/2001ASPC..245..162C) -- **Siyao** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/sum_chaboyer_2001_pre.pdf))
   * (2) Globular Cluster Ages/Cosmology: [Chaboyer et al. (1998)](http://adsabs.harvard.edu/abs/1998ApJ...494...96C) -- **Kareem** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/kareem_Chaboyer_1998.pdf))
  
  * **M 10/10**
   * (1) Multiple Populations in Globular Clusters: Observations [Milone et al. (2013)](http://adsabs.harvard.edu/abs/2013ApJ...767..120M) -- **Max** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/max_Milone2013.pptx))
   * (2) Multiple Populations in Globular Clusters: Theory [Renzini (2016)](http://adsabs.harvard.edu/abs/2015MNRAS.454.4197R) -- **Deepthi** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/deepthi_gc_multiplepops.pptx))

  * **W 10/12**
   * (1) Multiple Populations in Young Clusters I.: [Goudfrooij et al. (2016)](http://adsabs.harvard.edu/abs/2015MNRAS.450.1693G) --  **David**
   * (2) Multiple Populations in Young Clusters II.: [Niederhofer et al. (2016)](http://adsabs.harvard.edu/abs/2016A%26A...586A.148N) -- **Ned** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/ned_niederhofer16.pdf))

 * **M 10/17**
  * (1) Stellar Populations in the Local Group: [Tolstoy et al. (2009)](http://adsabs.harvard.edu/abs/2009ARA%26A..47..371T) -- **split between 2 people**

 * **W 10/19**
  * (1) Ultra-Faint Dwarf Galaxies: [Brown et al. (2014)](http://adsabs.harvard.edu/abs/2014ApJ...796...91B) -- **Saundra** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/saundra_Brown_2014_presentation.pdf))
  * (2) Satellites of M31: [Skillman et al. (2016)](http://adsabs.harvard.edu/abs/2016arXiv160601207S) -- **Irina** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/resolved_stars/irina_skillman2016-M31_Satellites.pdf))

* [Problem set #3](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps3.pdf) (assigned 10/3, due 10/17)
  

**4. Dust** (~10/24 - 11/2)

* **Topics covered:**  Dust Extinction, Commonly Used Attenuation Curves, Effects of Dust on Galaxy SEDs

* **Class Presentations:**

  * **M 10/24** 
   * (0) A few words on dust -- **Dan**
   * (1) Dust Attenuation in the Milky Way: [Cardelli et al. (1989)](http://adsabs.harvard.edu/abs/1989ApJ...345..245C) -- **Deepthi** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/deepthi_Cardelli89.pdf))
   * (2) Milky Way Foreground Dust: [Schlafly & Finkbeiner (2011)](http://adsabs.harvard.edu/abs/2011ApJ...737..103S) -- **Siayo** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/siyao_schlafly_pre.pdf))
  
 * **W 10/26** -- Dan out of town, Hans-Walter will talk about stellar spectroscopy.

 * **M 10/31**
  * (1) Dust in Starburst Galaxies: [Calzetti et al. (1994)](http://adsabs.harvard.edu/abs/1994ApJ...429..582C) -- **Max** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/max_Calzetti1994.pptx))
  * (2) Dust in the SMC: [Gordon & Clayton (1998)](http://adsabs.harvard.edu/abs/1998ApJ...500..816G) -- **Saundra** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/saundra_gordon_clayton_1998_presentation.pdf))
   
  * **W 11/2**
   * (1) The IRX-Beta Relationship: [Meurer et al. (1999)](http://adsabs.harvard.edu/abs/1999ApJ...521...64M) -- **Ned** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/IRX_beta.pptx))
   * (2) Dust Attenuation in Distant Galaxies: [Kriek & Conroy (2013)](http://adsabs.harvard.edu/abs/2013ApJ...775L..16K) -- **Irina** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/dust/irina_kriek2013-dust_variation.pdf))
 

* [Problem set #4](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps4.pdf) (assigned 10/24, due 11/7)


**5. Unresolved Galaxies** (~11/7 - 11/16)

* **Topics covered:**  SFR indicators, Stellar Mass-to-Light Ratios, Star Formation Histories, Metallicity Evolution

* **Class Presentations:**

 * **M 11/7** 
  * (1) Overview of SFR Indicators: [Kennicutt (1998)](http://adsabs.harvard.edu/abs/1998ARA%26A..36..189K) and [Kennicutt & Evans (2012), Section 3](http://adsabs.harvard.edu/abs/2012ARA%26A..50..531K) -- **Kareem** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/kareem_Kennicutt_1998.pdf)) + **Deepthi** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/deepthi_ay250-%20unresolved%20galaxies.pptx))
  

 * **W 11/9**
  * (1) Star Formation Histories of SDSS Galaxies: [Kauffmann et al. (2003)](http://adsabs.harvard.edu/abs/2003MNRAS.341...33K) -- **David** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/kauffmann2003.pdf))
  * (2) SFHs and IMF Variations: [Hoversten & Glazebrook (2008)](http://adsabs.harvard.edu/abs/2008ApJ...675..163H) -- **Max** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/max_HoverstenGlazebrook2008.pptx))
   
 * **M 11/14**  
  * (1) M/L Ratios. I: [Bell & de Jong (2001)](http://adsabs.harvard.edu/abs/2001ApJ...550..212B) -- **Irina** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/irina_bell2001-mass-to-light.pdf))
  * (2) Chemical Evolution: [Tinsley (1979)](http://adsabs.harvard.edu/abs/1979ApJ...229.1046T) -- **Siyao** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/siayo_beatrice_1979.pdf))

 * **W 11/16**
  * (1) Mass-Metallicity Relationship for 50,000 Galaxies: [Tremonti et al. (2004)](http://adsabs.harvard.edu/abs/2004ApJ...613..898T) --  **Saundra** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/saundra_tremonti_2004_presentation.pdf))
  * (2) Mass-Metallicity Relationship in Nearby Galaxies: [Berg et al. (2012)](http://adsabs.harvard.edu/abs/2012ApJ...754...98B) -- **Ned** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/unresolved_galaxies/ned_berg12.pdf))
 

* [Problem set #5](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps5.pdf) (assigned 11/7, due 11/21)
  

**6. High-Z Galaxies** (~11/21 - 11/30)

* **Topics covered:**  high-z galaxy identification, stellar populations, luminosity functions, galaxies & reionization

* **Class Presentations:**

 * **M 11/21** 
  * (1) High-redshift galaxy discovery and characterization: [Dunlop (2012)] (https://arxiv.org/abs/1205.1543) -- **Deepthi** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/highz/deepthi_dunlop12.pdf)) and **Ned** ([slides](https://github.com/dweisz/ay250_fall2016/blob/master/slides/highz/ned_dunlop12.pdf))

 * **W 11/23 -- No Class**
   
 * **M 11/28**  
  * (1) Galaxies in the First Billion Years: [Stark (2016)](http://adsabs.harvard.edu/abs/2016ARA%26A..54..761S) -- **David** and **Kareem**
  * (2) Stellar Populations, Binaries, and Reionization : [Stanway et al. (2016)](http://adsabs.harvard.edu/abs/2016MNRAS.456..485S) -- **Siyao**

 * **W 11/30**
  * (1) Stellar Populations & Binaries at z~2-3: [Steidel et al. (2016)](http://adsabs.harvard.edu/abs/2016ApJ...826..159S) -- **Max**
  * (2) Faint, lensed galaxies at high-z: [Livermore et al. (2016)](http://adsabs.harvard.edu/abs/2016arXiv160406799L) -- **Saundra**
  * (3) Challenges with faint, lensed galaxies at high-z: [Bouwens et al. (2016)](http://adsabs.harvard.edu/abs/2016arXiv161000283B) --  **Irina**

* [Problem set #6](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/ps6.pdf) (assigned 11/21, due 12/5)
 
**7. Final Project** (Pull Request **MUST** be accepted by 12/12)

 Projects from each pair must proposed and approved by 11/23.

 Final project overview is [here](https://github.com/dweisz/ay250_fall2016/blob/master/problem_sets/finalproject_overview.pdf).

Final Projects: 
 * **Siyao** and **Ned**: Figures 3-7 from Conroy et al. (2009)
 * **Saundra** and **Deepthi**: Evolution of Stellar masses as a function of various bands for sparse parameters grids for SFH=1,4.
 * **Irina** and **Max**: Figure 2 from Conroy et al (2010)
 * **David** and **Kareem**: Figure 9 from Conroy et al. (2009)


**Class Overview, Review, and Discussion: 12/5, 10-11:30am in 501b**


#### Software

Problem sets will require the use of github.  Each student will need their own github account and a public repository specifically for this class.  Problem sets should all be done in your own public repository. For those new to github, it has a gentle learning curve and most questions can be addressed simply with [this tutorial](https://guides.github.com/activities/hello-world/) and/or via Google.  

Problem sets involving coding should be done using python and jupyter (formerly iPython notebook). Any flavor of python is fine, although the [Anaconda distribution](https://www.continuum.io) is highly recommended. University affiliates can get it for [free](https://www.continuum.io/anaconda-academic-subscriptions-available).

[jupyter](http://jupyter.org) is an excellent web-based coding/python notebook that allows you to easily track and transparently share your code, as well as display key plots inline.  

In addition to the standard python installation, we will also use these python packages:

* [emcee](http://dan.iel.fm/emcee/current)
* [fsps](https://github.com/cconroy20/fsps)
* [python-fsps](http://dan.iel.fm/python-fsps/current/)
* [prospector](https://github.com/bd-j/prospector)
* [corner](http://corner.readthedocs.io/en/latest)

fsps and python-fsps can, at times, be tricky to install. Give yourself plenty of time to install and troubleshoot before we need to use them in class.
