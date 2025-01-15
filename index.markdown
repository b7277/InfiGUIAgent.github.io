---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection">
  <meta name="keywords" content="OS-Agents, MLLM, MLLM-based, computing-devices-use, GUI-Agent, computer-use, GUI, web-agent, multimodal-large-language-model, large-language-model, phone-use">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection</title>
  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro" rel="stylesheet">

  <link rel="stylesheet" href="./static/css/bulma.min.css">
  <link rel="stylesheet" href="./static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./static/css/fontawesome.all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./static/css/index.css">

  <link rel="stylesheet" href="./bower_components/bootstrap/dist/css/bootstrap.table.min.css">
  <!--  <link rel="stylesheet" href="bower_components/bootstrap/dist/css/bootstrap.min.css">-->
  <link rel="stylesheet" href="./stylesheets/layout.css">
  <link rel="stylesheet" href="./stylesheets/index.css">

  <!-- for print the table -->
  <script type="text/javascript" charset="utf8" src="https://code.jquery.com/jquery-3.6.0.slim.min.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/jquery.dataTables.css">
  <script type="text/javascript" charset="utf8" src="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.js"></script>

  <link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.11.3/css/dataTables.bootstrap5.min.css">
  <script src="https://cdn.datatables.net/1.11.3/js/dataTables.bootstrap5.min.js"></script>

  <link rel="icon" href="./static/images/logo.jpg">

  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>
</head>

<body>

  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
    <div class="navbar-menu">
      <div class="navbar-start" style="flex-grow: 1; justify-content: center;">
        <a class="navbar-item" href="https://github.com/OS-Agent-Survey">
          <span class="icon">
            <i class="fas fa-home"></i>
          </span>
        </a>

	<!-- 修改团队主页 -->

        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">
            More
          </a>
          <div class="navbar-dropdown">
            <a class="navbar-item" href="https://infiagent.github.io/">
              InfiAgent-DABench: Evaluating Agents on Data Analysis Tasks
            </a>
          </div>
        </div>
      </div>

    </div>
  </nav>

  <div class="container">
    <div class="column has-text-centered">
      <img style="max-width: 200px; margin-bottom: -50px;" src="static/images/logo.jpg">
    </div>
  </div>
  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title" style=" font-size:2.3rem;">InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection<br>
            </h1>


            <div class="is-size-5 publication-authors">
              <span class="author-block">
		<a href="#" style="text-decoration: none; color: blue;">Yuhang Liu</a><sup style="color: #6fbf73;">1</sup>,
                <a href="#" style="text-decoration: none; color: blue;">Pengxiang Li</a><sup style="color: #6fbf73;">2</sup>, 
		<a href="#" style="text-decoration: none; color: blue;">Zishu Wei</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Congkai Xie</a><sup style="color: #6fbf73;">3</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Xueyu Hu</a><sup style="color: #6fbf73;">1</sup>,
   		<a href="#" style="text-decoration: none; color: blue;">Xinchen Xu</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Shengyu Zhang</a><sup style="color: #ffac33;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Xiaotian Han</a><sup style="color: #ed4b82;">4</sup>,  
		<a href="#" style="text-decoration: none; color: blue;">Hongxia Yang</a><sup style="color: #007bff;">5</sup>,
	     	<a href="#" style="text-decoration: none; color: blue;">Fei Wu</a><sup style="color: #6fbf73;">1</sup>,<br>
		</span>
          </div>
	       <div class="is-size-5 publication-authors"> 
	       <span class="author-block"><sup style="color:#6fbf73;">1</sup>Zhejiang University </span>
	       <span class="author-block"><sup style="color:#ffac33;">2</sup>Dalian University of Technology </span>
	       <span class="author-block"><sup style="color:#ed4b82;">3</sup>Reallm Labs </span><br>
	       <span class="author-block"><sup style="color:#007bff;">4</sup>ByteDance Inc </span><br>
	       <span class="author-block"><sup style="color:#ff0000;">5</sup>The Hong Kong Polytechnic University </span><br>
	      
	      <a href="#" style="text-decoration: none; color: blue;">sy_zhang@zju.edu.cn,</a><br>
       	      <a href="#" style="text-decoration: none; color: blue;">xiaotian.han@bytedance.com,</a><br>
              <a href="#" style="text-decoration: none; color: blue;">hongxia.yang@polyu.edu.hk</a><br>

              <br>
              <!-- <span class="author-block">
                Main Maintainer: <a href="mailto:xxxxx">xxxxx</a>
              </span> -->
              <!-- <span class="author-block">
                <a href="https://xxx.github.io/">xxxxxx</a><sup>1</sup></span>
			        <br/> -->
            </div>

            <div class="is-size-5 publication-authors">
              <!-- <span class="author-block"><sup>1</sup>Caption of Quận 5, Ho Chi Minh City, Vietnam</span> -->
              <!-- <span class="author-block"><sup>2</sup>Peking University,</span> -->
            </div>

            <div class="column has-text-centered">
              <div class="publication-links">
                <!-- PDF Link. -->
                <span class="link-block">
                  <a href="https://infiguiagent.github.io/paper.pdf"
                    class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
          	      <i class="fas fa-file-pdf" style="color:white"></i>

                    </span>
                    <span>Paper</span>
                  </a>
                </span>
                <!-- Repo Link. -->
                <span class="link-block">
                  <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Repository</span>
                  </a>
                  <!-- <a href="https://github.com/infi-coder/inficoder-eval-framework"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Evaluation Repo</span>
                  </a> -->
                </span>
                <!-- Twitter Link. -->
                <!-- <span class="link-block">
                  <a href="https://twitter.com/taoyds/status/1595086401309388801"
                    class="external-link button is-normal is-rounded is-dark">
                    <span class="icon">
                      <i class="fab fa-twitter"></i>
                    </span>
                    <span>Twitter</span>
                  </a>
                </span> -->
		
		<!-- Zhihu Link. -->
		<span class="link-block">
		  <a href="https://zhuanlan.zhihu.com/p/14143950360"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/zhihu_logo_website_v2.png" alt="Zhihu Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>Zhihu</span>
		  </a>
		</span>

		<!-- openreview Link. -->
		<span class="link-block">
		  <a href="https://openreview.net/forum?id=I7ODESoF6k"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/openreview_v3.jpg" alt="Zhihu Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>OpenReview</span>
		  </a>
		</span>

              <!-- Twitter Link. -->
		<span class="link-block">
		  <a href="https://x.com/OSAgentSurvey/status/1876301310179660231"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/twitter_v4.jpg" alt="X Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>Twitter</span>
		  </a>
		</span>
  
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


<section class="hero" style="margin-top: -40px !important;">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">
          <div class="is-size-5 publication-authors">
            <span class="author-block">
              <!-- 主标题部分 -->
              <span style="color: #FF0000; font-size: 30px; font-weight: bold;">❗Why is there no arXiv link for this paper?</span><br>
              <!-- 描述正文 -->
              <span style="color: #FF0000; font-size: 16px; line-height: 1.6;">
               This paper was <span style="font-weight: bold;">rejected by arXiv</span> with the justification: 
                "Our moderators determined that your submission <span style="font-weight: bold;">does not contain sufficient original or substantive scholarly research and is not of interest to arXiv</span>." 
                This reasoning appears to be <span style="font-weight: bold;">inconsistent with the content and contribution of the paper</span>. We attempted an 
                <span style="font-weight: bold;">appeal</span>, but unfortunately, this was unsuccessful, and <span style="font-weight: bold;">no further explanation was provided</span>. 
                A resubmission did not resolve the issue either. As a result, the ONLY way to access the paper at the moment is through our 
                <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey/tree/main" style="text-decoration: none; color: #b20000 !important;"><b>GitHub Repository</b></a> or via <a href="https://openreview.net/forum?id=I7ODESoF6k" style="text-decoration: none; color: #b20000 !important;"><b>OpenReview Archive</b></a>.
                We are disappointed by the lack of transparency in arXiv’s moderation process.
              </span><br><br>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>



  <section class="section" style="margin-top: -40px !important;">
    <div class="container is-max-desktop">
      <!-- Abstract. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='overview-of-xxx'>Overview of Survey</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <p>
 		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/os_agent_evolutionary_tree_version_github.jpg">
		    
 	This project conducts a comprehensive survey on OS Agents, which are <span style="font-weight: bold;">(M)LLM-based agents that use computing devices (e.g., computers and mobile phones) by operating within the environments and interfaces (e.g., Graphical User Interface (GUI)) provided by operating systems (OS) to automate tasks</span>. The survey begins by elucidating the fundamentals of OS Agents, exploring their key components including the environment, observation space, and action space, and outlining essential capabilities such as understanding, planning, and grounding. Methodologies for constructing OS Agents are examined, with a focus on domain-specific foundation models and agent frameworks. A detailed review of evaluation protocols and benchmarks highlights how OS Agents are assessed across diverse tasks. Finally, current challenges and promising future research directions, including safety and privacy, personalization and self-evolution, are discussed. Ultimately, we hope this study will serve as a catalyst for innovation, driving meaningful progress in both academia and industry.<br>
  		
    	     <img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/survey_overview_2.jpg">
  
            </p>
          </div>
        </div>
      </div>
      <!--/ Abstract. -->
    </div>
  </section>

 


  <section class="section">
    <div class="container is-max-desktop">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='contact'>Contact</h2>
          <div class="content has-text-justified">
            <p>
              Please let us know if you find out a mistake or are interested in contributing by e-mail: <a href='mailto:huxueyu.zju@gmail.com' target='_blank' class='url'>huxueyu.zju@gmail.com</a>.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

<section class="section">
  <div class="container is-max-desktop">
    <div class="columns is-centered has-text-centered">
      <div class="column is-four-fifths">
        <h2 class="title is-3" id="contact">Citation</h2>
        <div class="content has-text-justified">
           <!--
	     <p>	
            <span style="color: #FF0000; font-size: 18px; font-weight: bold;">Caution:</span> Considering that the <b>current bib citation points to our repository</b>, we will <b>update it to point to the paper as soon as the preprint server is available</b>. Please stay tuned for updates. Before this, if you find our repository helpful, we would appreciate it if you could cite:
          </p> 
          -->
          <p>If you find our work valuable for your research or applications, we would greatly appreciate a star ⭐ and a citation using the BibTeX entry provided below.</p> 
          <pre><code>@article{202412.2294,
	doi = {10.20944/preprints202412.2294.v1},
	url = {https://doi.org/10.20944/preprints202412.2294.v1},
	year = 2024,
	month = {December},
	publisher = {Preprints},
	author = {Xueyu Hu and Tao Xiong and Biao Yi and Zishu Wei and Ruixuan Xiao and Yurun Chen and Jiasheng Ye and Meiling Tao and Xiangxin Zhou and Ziyu Zhao and Yuhuai Li and Shengze Xu and Shawn Wang and Xinchen Xu and Shuofei Qiao and Kun Kuang and Tieyong Zeng and Liang Wang and Jiwei Li and Yuchen Eleanor Jiang and Wangchunshu Zhou and Guoyin Wang and Keting Yin and Zhou Zhao and Hongxia Yang and Fan Wu and Shengyu Zhang and Fei Wu},
	title = {OS Agents: A Survey on MLLM-Based Agents for General Computing Devices Use},
	journal = {Preprints}
}</code></pre>
        </div>
      </div>
    </div>
  </div>
</section>

<footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <a class="icon-link" href="https://os-agent-survey.github.io/paper.pdf">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/OS-Agent-Survey/OS-Agent-Survey">
          <i class="fab fa-github" style="color:white"></i>
        </a>
      </div>
      <div class="columns is-centered">
        <div class="column is-8">
          <div class="content">
            <p>
              This website is adapted from <a href="https://ds1000-code-gen.github.io/">ds1000-code-gen.github.io</a> and is licensed under a <a rel="license"
                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
                Commons Attribution-ShareAlike 4.0 International License</a>.
            </p>
            <p>
              This means you are free to borrow the <a href="https://github.com/OS-Agent-Survey/OS-Agent-Survey.github.io">source
                code</a> of this website,
              we just ask that you link back to this page in the footer.
            </p>
          </div>
        </div>
      </div>
    </div>
 </footer>

  <script>
    $(document).ready( function () {
      $('.mainTable').DataTable({ordering: true, order: [[4, 'desc']], columns: [{ "type": "num" },{ "type": "html" },{ "type": "num" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "num-fmt" },{ "type": "html", "orderable": false }]});
    } );
  </script>

</body>

</html>
