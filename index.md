---
layout: landing
---



<!-- Banner -->
<section id="banner">
	<div class="inner">
		<h2>{{ site.title }}</h2>
		<p>{{ site.description | markdownify }}</p>
		<ul class="actions">
			<li><a href="#" class="button special">Curriculum Vitae</a></li>
		</ul>
	</div>
	<a href="#one" class="more scrolly">Know Me More</a>
</section>

<!-- One -->
<section id="one" class="wrapper style1 special">
	<div class="inner">
		<header class="major">
			<h3>Personal Information</h3>
			<p>I am a 5th-year PhD student at <a href="https://publichealth.yale.edu/biostat/">Yale Biostatistics Department</a>.
			My advisor is <a href="http://zhaocenter.org">Dr. Hongyu Zhao</a>.
			My research lies in applying longitudinal data analysis
			in the Bayesian framework to high dimensional gene expression data. </p>
			<h4>Education</h4>
			<br />
			<p align="center">2012-2017 Ph.D. in Biostatistics, Yale University <br />
			2010-2012 ScM. in Biostatistics, Johns Hopkins University <br />
			2006-2010 B.E. in Bioinformatics, Huazhong University of Science and Technology</p>
			<h4>Selected Honors and Awards</h4>
			<br />
			<p> HHMI international student research fellowship - University Nominee (Yale 2015)<br />
			Kocherlakota Award from department (JHU 2011)</p>
		</header>
		<ul class="icons major">
			<li><a id="test1" href="#two" title='Research'><span class="icon fa-diamond major style1"></span></a></li>
			<li><a id="test2" href="#" title='Interest'><span class="icon fa-heart-o major style2"></span></a></li>
			<li><a id="test3" href="#" title='Links'><span class="icon fa-code major style3"></span></a></li>
		</ul>
	</div>
</section>
<!-- Two -->
  <section id="two" class="wrapper alt style2">
    <section class="spotlight">
      <div class="image"><img src="images/pic01.jpg" alt="" /></div>
      <div class="content">
        <h2>Magna primis lobortis<br />
        sed ullamcorper</h2>
        <p>Aliquam ut ex ut augue consectetur interdum. Donec hendrerit imperdiet. Mauris eleifend fringilla nullam aenean mi ligula.</p>
      </div>
    </section>
    <section class="spotlight">
      <div class="image"><img src="images/pic02.jpg" alt="" /></div>
      <div class="content">
        <h2>Tortor dolore feugiat<br />
        elementum magna</h2>
        <p>Aliquam ut ex ut augue consectetur interdum. Donec hendrerit imperdiet. Mauris eleifend fringilla nullam aenean mi ligula.</p>
      </div>
    </section>
    <section class="spotlight">
      <div class="image"><img src="images/pic03.jpg" alt="" /></div>
      <div class="content">
        <h2>Augue eleifend aliquet<br />
        sed condimentum</h2>
        <p>Aliquam ut ex ut augue consectetur interdum. Donec hendrerit imperdiet. Mauris eleifend fringilla nullam aenean mi ligula.</p>
      </div>
    </section>
  </section>

<!-- Three -->
  <section id="three" class="wrapper style3 special">
    <div class="inner">
      <header class="major">
        <h2>Publication and Software</h2>
        <p align="left">

7. <b>Jiehuan Sun</b>, Jose D. Herazo-Maya†, Xiu Huang, Naftali Kaminski, and Hongyu Zhao. "Distance-correlation based gene set analysis in longitudinal studies". <i>Manuscript</i>. <br />
<br />
6. <b>Jiehuan Sun</b>, Jose D. Herazo-Maya, Naftali Kaminski, Hongyu Zhao, and Joshua L. Warren. "A dirichlet process mixture model for clustering longitudinal gene expression data". <i>Manuscript</i>. <br />
<br />
5. <b>Jiehuan Sun</b>, Joshua L. Warren, and Hongyu Zhao. "A Bayesian semiparametric factor analysis model for subtype identificatio". <i>Manuscript</i>. <br />
<br />
4. Qiongshi Lu, Yiming Hu, <b>Jiehuan Sun</b>, Yuwei Cheng, Kei-Hoi Cheung, and Hongyu Zhao. ”A Statistical Framework to Predict Functional Non-Coding Regions in the Human Genome Through Integrated Analysis of Diverse Types of Annotation Data.” <i>Scientific reports</i> 5 (2015). [<a href="http://www.nature.com/articles/srep10576">Link</a>] <br />
<br />
3. <b>Jiehuan Sun</b> and Hongyu Zhao. ”The application of sparse estimation of covariance matrix to quadratic discriminant analysis.” <i>BMC bioinformatics</i> 16.1 (2015): 48. [<a href="http://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-014-0443-6">Link</a>]<br />
<br />
2. <b>Jiehuan Sun</b>, Xintao Hu, Xiu Huang, Yang Liu, Kaiming Li, Xiang Li, Junwei Han, Lei Guo, Tianming Liu, and Jing Zhang. ”Inferring consistent functional interaction patterns from natural stimulus FMRI data.” <i>NeuroImage</i> 61, no. 4 (2012): 987-999. [<a href="http://www.sciencedirect.com/science/article/pii/S1053811912002868">Link</a>]<br />
<br />
1. Jian Yu, Xiaobin Xing, Lingyao Zeng, <b>Jiehuan Sun</b>, Wei Li, Han Sun, Ying He et al. ”SyStem-Cell: a database populated with multiple levels of experimental data from stem cell differentiation research.” <i>PloS one</i> 7, no. 7 (2012): e35230. [<a href="http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0035230">Link</a>]<br />


				</p>
      </header>
      <ul class="features">
        <li class="icon fa-laptop">
          <h3><a href="https://cran.r-project.org/web/packages/SQDA/index.html">sQDA</a></h3>
          <p>R package to perform Sparse Quadratic Discriminant Analysis (SQDA) with the assumption of block-diagonal and sparse covariance matrix. SQDA is useful in classification of high-dimensional gene expression data, with the consideration of the genetic network rewiring in subclasses. </p>
        </li>
        <li class="icon fa-heart-o">
          <h3><a href="https://www.bioconductor.org/packages/release/bioc/html/dcGSA.html">dcGSA</a></h3>
          <p>Bioconductor package to perform distance-correlation based Gene Set Analysis (dcGSA) for longitudinal gene expression profiles. The dcGSA package is useful to assess the associations between gene sets and outcomes, considering both expression profiles and clinical outcomes' longitudinal nature.</p>
        </li>
        <li class="icon fa-flag-o">
          <h3><a href="http://genocanyon.med.yale.edu">GENOCANYON</a></h3>
          <p>Whole-genome functional annotation approach based on unsupervised statistical learning. It integrates genomic conservation measures and biochemical annotation data to predict the functional potential at each nucleotide.</p>
        </li>
      </ul>

    </div>
  </section>


<section id="four" class="wrapper style1 special">
  <div class="inner">
	<header class="major">
		<h2>Conferences</h2>
		<br />
		<h4>Poster and Workshop</h4>
		<ul align="left">
		<li>The 29th New England Statistics Symposium April 24-25, 2015 • Bioinformatics Transition Workshop - SAMSI<br /> May 11-13, 2015. </li>
		<li>Statistical and Computational Challeges in Omics Data Integration workshop - SAMSI<br /> Feb. 16-17, 2015.</li>
		<li>2014 Rutgers Statistics Symposium Statistics and the Century of Data<br /> May 2, 2014.</li>
		<li>Statistical Methods for Very Large Datasets Conference<br /> June 1st-3rd, 2011.</li>
		<li>The 9th China-Japan-Korea Bioinformatics Training Course and Bioinformatics Symposium<br /> April 20th-23rd, 2010. </li>
		</ul>
		<h4>Talk</h4>
		<ul align="left">
		<li>"Discovery of Novel Loci Associated with COPD by Pooling Information from Related Clinical Feature and Functional Annotation" <br /> <i>ENAR Spring Meeting</i>, Mar. 6-9, 2016. </li>
		<li>“Discovery of Novel Loci Associated with COPD by Pooling Information from Case-control status, Related Clinical Feature, and Functional Annotation” <br /><i>Statistical and Computational Challeges in Omics Data Integration workshop - SAMSI</i>, Feb. 16-17, 2015.</li>
		<li>“Discovery of Novel Loci Associated with COPD by Pooling Information from Related Clinical Feature and Functional Annotation”<br /> <i>Bioinformatics Transition Workshop - SAMSI</i>, May 11-13, 2015.</li>
		<li>“The application of sparse estimation of covariance matrix to quadratic discriminant analysis”<br /> <i>The 29th New England Statistics Symposium</i>, April 24-25, 2015.</li>

		</ul>
	</header>
	</div>
</section>





<!-- CTA -->
<section id="cta" class="wrapper style4">
	<div class="inner">

		<header>
			<h2>Contact me</h2>
			<p>Address: 60 College Street, New Haven CT 06520 <br />
			Email: jiehuan DOT sun AT yale DOT edu</p>
		</header>
		<ul class="actions vertical">
			<li><a href="#" class="button fit special"> My Interests</a></li>
			<li><a href="#" class="button fit">More Links</a></li>
		</ul>
	</div>
</section>
