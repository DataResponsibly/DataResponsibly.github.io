---
title: DataResponsibly - Course
layout: default_course
excerpt: "Data Responsibly - Course"
sitemap: false
permalink: /course/
author: Julia Stoyanovich
---


<div class="container-lg px-3 my-5 markdown-body">

  <h1><a href="{{ site.baseurl }}/course">DS-GA 3001.009: Special Topics in Data Science:<br> Responsible Data Science</a></h1>

  <h2>New York University, Center for Data Science, Spring 2019</h2>


  <p><strong>Lecture:</strong> Mondays from 11am-12:40pm; <strong>Lab:</strong> Thursdays from 5:20pm-6:10pm</p>
  <p><strong>Location:</strong>60 5th Avenue, Room 110</p>

  <p><strong>Instructor:</strong> <a href="https://engineering.nyu.edu/faculty/julia-stoyanovich">Julia Stoyanovich</a>, Assistant Professor of Data Science, Computer Science and Engineering.<br>
  Office hours Mondays 1:30-3pm or by appointment, at 60 5th Avenue, Room 605.</p>

  <p><strong>Section Leader:</strong> <a href="mailto:ug200@nyu.edu">Udita Gupta</a>.
  Office hours Thursdays 4-5pm at 60 5th Avenue, Room 606.</p>

  <p><strong>Syllabus:</strong> <a href="https://dataresponsibly.github.io/documents/Syllabus_DS-GA-3001.009_SP_2019.pdf">pdf</a></p>

  <p><strong>Course Description:</strong>
    The first wave of data science focused on accuracy and
    efficiency -- on what we <em>can</em> do with data. The second
    wave focuses on responsibility -- on what we <em>should</em>
    and <em>shouldn't</em> do. Irresponsible use of data science can
    cause harm on an unprecedented scale. Algorithmic changes in
    search engines can sway elections and incite violence;
    irreproducible results can influence global economic policy;
    models based on biased data can legitimize and amplify racist
    policies in the criminal justice system; algorithmic hiring
    practices can silently and scalably violate equal opportunity
    laws, exposing companies to lawsuits and reinforcing the feedback
    loops that lead to lack of diversity.  Therefore, as we develop
    and deploy data science methods, we are compelled to think about
    the effects these methods have on individuals, population groups,
    and on society at large.</p>

 <p>Responsible Data Science is a technical course that tackles the
   issues of ethics, legal compliance, data quality, algorithmic
   fairness and diversity, transparency of data and algorithms,
   privacy, and data protection. The course is developed and taught by
   <a
   href="https://engineering.nyu.edu/faculty/julia-stoyanovich">Julia
   Stoyanovich</a>, Assistant Professor at the Center for Data Science
   and at the Tandon School of Engineering, and member of the <a
   href="https://www1.nyc.gov/office-of-the-mayor/news/251-18/mayor-de-blasio-first-in-nation-task-force-examine-automated-decision-systems-used-by">NYC
   Automated Decision Systems Task Force</a>.</p>

 <p><strong>Prerequisites:</strong> Introduction to Data Science,
 Introduction to Computer Science, or similar courses.</p>

  <h2 id="hdr-read-req">Background Reading (required)</h2>
   <ul>
    <li>Barocas and Selbst (2016) "Big Data’s Disparate
    Impact" <a href="http://www.californialawreview.org/wp-content/uploads/2016/06/2Barocas-Selbst.pdf">pdf</a></li>
    <li>White House Report on Big Data (2014) "Big Data: Seizing
    Opportunities, Preserving
    Values" <a href="https://obamawhitehouse.archives.gov/sites/default/files/docs/big_data_privacy_report_may_1_2014.pdf">pdf</a></li>
    <li>Brauneis and Goodman (2017) "Algorithmic Transparency for the
    Smart
    City" <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3012499">pdf</a></li>
    <li>Kroll et al. (2017) "Accountable
    Algorithms" <a href="https://scholarship.law.upenn.edu/penn_law_review/vol165/iss3/3/">pdf</a></li>
   </ul>

 <h2 id="hdr-read-opt">Background Reading (optional)</h2>
   <ul>
    <li>Matthew Salganik "Bit by Bit: Social Research in the Digital Age" (<a href="https://www.bitbybitbook.com/en/1st-ed/preface/">read online</a>)</li>
    <li>Cathy O’Neil "Weapons of Math Destruction"</li>
    <li>Frank Pasquale "The Black Box Society"</li>
    <li>Virginia Eubanks "Automating Inequality"</li>
   </ul>

  <h2 id="hdr-sch">Schedule</h2>

  <p>This weekly schedule is tentative and is subject to change.</p>

  <table>
    <thead>
      <tr>
        <th style="text-align: left">Date</th>
        <th style="text-align: left">Topic</th>
        <th style="text-align: left">Materials</th>
        <th style="text-align: left">Assignments</th>
      </tr>
    </thead>
    <tbody>
      <!-- WEEK 1 -->
      <tr>
        <td style="text-align: left" nowrap>Jan 28</td>
        <td style="text-align: left"><b>Lecture:</b> Introduction and background<br>
                                    <i>Topics:</i> Course outline, aspects of responsibility in data science through recent examples.<br>
                                    <i>Reading:</i><br>         
         "Bias in Computer Systems", Friedman and Nissenbaum (1996) <a href="https://dl.acm.org/citation.cfm?id=230561">ACM DL</a><br>
        "Machine Bias", Angwin, Larson, Mattu, Kirchner (2016) <a href="https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing">ProPublica</a><br>
        "Data, Responsibly", Abiteboul and Stoyanovich (2015) <a href="http://wp.sigmod.org/?p=1900">ACM SIGMOD blog</a>
        </td>
        <td style="text-align: left">
            <a href="https://dataresponsibly.github.io/documents/Lecture1.pdf">slides</a>
        </td>
        <td style="text-align: left"></td>
      </tr>
      <tr>
        <td style="text-align: left" nowrap>Jan 31</td>
        <td style="text-align: left"><b>Lab</b>: ProPublica's Machine Bias<br>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
      <!-- WEEK 2 -->
      <tr>
        <td style="text-align: left" nowrap>Feb 4</td>
        <td style="text-align: left"><b>Lecture:</b> Fairness<br>
                                     <i>Topics:</i> A taxonomy of fairness definitions; individual and group fairness. The importance of a socio-technical perspective: stakeholders and trade-offs.<br>
                                     <i>Reading:</i><br>
        "Big Data's Disparate Impact", Barocas and Selbst (2016) <a href="http://www.californialawreview.org/wp-content/uploads/2016/06/2Barocas-Selbst.pdf">pdf</a><br>
        “Fairness through awareness”, Dwork, Hardt, Pitassi, Reingold, Zemel (2012) <a href="https://dl.acm.org/citation.cfm?doid=2090236.2090255">ACM DL</a><br>
        "On the (im)possibility of fairness", Friedler, Scheidegger, Venkatasubramanian (2016) <a href="https://arxiv.org/abs/1609.07236">arXiv</a>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
      <tr>
        <td style="text-align: left" nowrap>Feb 7</td>
        <td style="text-align: left"><b>Lab</b>: IBM's AI Fairness 360 toolkit</td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
      <!-- WEEK 3 -->
      <tr>
        <td style="text-align: left" nowrap>Feb 11</td>
        <td style="text-align: left"><b>Lecture:</b> Fairness<br>
                                    <i>Topics:</i> Impossibility results; causal definitions; fairness beyond classification.<br>
                                    <i>Reading:</i><br>       
        "Fair prediction with disparate impact: A study of bias in recidivism prediction instruments", Chouldechova (2017) <a href="https://arxiv.org/abs/1703.00056">arXiv</a><br>
        "Prediction-Based Decisions and Fairness: A Catalogue of Choices, Assumptions, and Definitions", Mitchell, Porash, Barocas (2018) <a href="https://arxiv.org/abs/1811.07867">arXiv</a>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Feb 14</td>
        <td style="text-align: left"><b>Lab</b>: IBM's AI Fairness 360 toolkit</td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW1 assigned</td>
      </tr>
      <!-- WEEK 4 -->
      <tr>
        <td style="text-align: left" nowrap>Feb 18</td>
        <td style="text-align: left"><b>No class, university holiday</b>                                    
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Feb 21</td>
  <td style="text-align: left"><b>Lab</b>: TBD </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
  <!-- WEEK 5 -->
      <tr>
        <td style="text-align: left" nowrap>Feb 25</td>
        <td style="text-align: left"><b>Lecture</b>:Anonymity and privacy<br>
                                   <i>Topics: Overview of responsible data sharing. Anonymization techniques; the limits of anonymization. Harms beyond re-identification.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW1 due</td>
      </tr>
      <tr>
        <td style="text-align: left" nowrap>Feb 28</td>
        <td style="text-align: left"><b>Lab</b>: Data Synthesizer
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW2 assigned</td>
      </tr>
      <!-- WEEK 6 -->
      <tr>
        <td style="text-align: left" nowrap>Mar 4</td>
        <td style="text-align: left"><b>Lecture</b>: Anonymity and privacy<br>
                                   <i>Topics: Differential privacy; privacy-preserving synthetic data generation; exploring the privacy / utility trade-off.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
      <tr>
        <td style="text-align: left" nowrap>Mar 7</td>
        <td style="text-align: left"><b>Lab</b>: Anonymity and privacy
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
  <!-- WEEK 7 -->
      <tr>
        <td style="text-align: left" nowrap>Mar 11</td>
        <td style="text-align: left"><b>Lecture</b>: Data science lifecycle, data profiling<br>
                                  <i>Topics: Overview of the data science lifecycle. Data profiling and validation. Is my dataset "biased"? The limits of data profiling. Data provenance. </i>
        </td>
  <td style="text-align: left"></td>
  <td style="text-align: left">HW2 due</td>
      </tr>
        <tr>
        <td style="text-align: left" nowrap>Mar 14 </td>
        <td style="text-align: left"><b>Lab</b>: Data cleaning
        </td>
  <td style="text-align: left"></td>
  <td style="text-align: left"></td>
      </tr>
      <!-- WEEK 8 -->
      <tr>
        <td style="text-align: left" nowrap>Mar 18</td>
        <td style="text-align: left"><b>No class, university holiday</b>                                    
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Mar 21</td>
  <td style="text-align: left"><b>No class, university holiday</b> </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
  <!-- WEEK 9 -->
      <tr>
        <td style="text-align: left" nowrap>Mar 25</td>
        <td style="text-align: left"><b>Lecture</b>: Data cleaning<br>
                                  <i>Topics: Qualitative and quantitative error detection. Missing attribute values and imputation. Outlier detection; duplicate detection. Documenting data cleaning transformations.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
        <tr>
        <td style="text-align: left" nowrap>Mar 28</td>
        <td style="text-align: left"><b>Lab</b>: Data cleaning
        </td>     
        <td style="text-align: left"></td>
        <td style="text-align: left">HW3 assigned</td>
      </tr>
  <!-- WEEK 10 -->
      <tr>
        <td style="text-align: left" nowrap>Apr 1</td>
        <td style="text-align: left"><b>Lecture</b>: Transparency<br>
                                  <i>Topics: Auditing black-box models; explainable machine learning; software testing.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Apr 4</td>
        <td style="text-align: left"><b>Lab</b>: LIME
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
      <!-- WEEK 11 -->
      <tr>
        <td style="text-align: left" nowrap>Apr 8</td>
        <td style="text-align: left"><b>Lecture</b>: Transparency<br>
                                  <i>Topics: Online price discrimination, transparency in online ad delivery.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW3 due</td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Apr 11</td>
        <td style="text-align: left"><b>Lab</b>: Quantitative Input Influence
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW4 assigned</td>
      </tr>
  <!-- WEEK 12 -->
      <tr>
        <td style="text-align: left" nowrap>Apr 15</td>
        <td style="text-align: left"><b>Lecture</b>: From transparency to accountability<br>
                                  <i>Topics: Transparency and accountability.  Legal frameworks: GDPR and the right to explanation; NYC ADS transparency law.  From auditing to interpretability.</i>
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Apr 18</td>
        <td style="text-align: left"><b>Lab</b>: Final review
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
  <!-- WEEK 13 -->
      <tr>
        <td style="text-align: left" nowrap>Apr 22</td>
        <td style="text-align: left"><b>Lecture</b>: Final exam (in class)
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">HW4 due</td>
      </tr>
       <tr>
        <td style="text-align: left" nowrap>Apr 25 </td>
        <td style="text-align: left"><b>Lab</b>: Nutritional labels
        </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">Project assigned</td>
      </tr>
  <!-- WEEK 14 -->
      <tr>
        <td style="text-align: left" nowrap>Apr 29</td>
        <td style="text-align: left"><b>Lecture</b>: Diversity<br>
                                   <i>Topics: Background on diversity in information retrieval, recommender systems and crowdsourcing; diversity models and algorithms; diversity vs. fairness; trade-offs between diversity and utility.</i>
       </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
     <tr>
        <td style="text-align: left" nowrap>May 2</td>
        <td style="text-align: left"><b>Lab</b>: Diversity
       </td>
       <td style="text-align: left"></td>
       <td style="text-align: left"></td>
      </tr>
   <!-- WEEK 15 -->
      <tr>
        <td style="text-align: left" nowrap>May 6</td>
        <td style="text-align: left"><b>Lecture</b>: Reproducibiilty<br>
       </td>
        <td style="text-align: left"></td>
        <td style="text-align: left"></td>
      </tr>
     <tr>
        <td style="text-align: left" nowrap>May 9</td>
        <td style="text-align: left"><b>Lab</b>: Reproducibility
       </td>
       <td style="text-align: left"></td>
       <td style="text-align: left"></td>
      </tr>
   <!-- WEEK 16 -->
      <tr>
        <td style="text-align: left" nowrap>May 13</td>
        <td style="text-align: left"><b>Lecture</b>: Project presentations
       </td>
        <td style="text-align: left"></td>
        <td style="text-align: left">Project report due</td>
      </tr>
    </tbody>


  </table>

 </div>
