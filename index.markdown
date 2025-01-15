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
        <a class="navbar-item" href="https://github.com/Reallm-Labs/InfiGUIAgent">
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
   		<a href="#" style="text-decoration: none; color: blue;">Xinchen Xu</a><sup style="color: #6fbf73;">1</sup>,<br>
		<a href="#" style="text-decoration: none; color: blue;">Shengyu Zhang</a><sup style="color: #ffac33;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Xiaotian Han</a><sup style="color: #ed4b82;">4</sup>,  
		<a href="#" style="text-decoration: none; color: blue;">Hongxia Yang</a><sup style="color: #007bff;">5</sup>,
	     	<a href="#" style="text-decoration: none; color: blue;">Fei Wu</a><sup style="color: #6fbf73;">1</sup>,<br>
		</span>
          </div>
	       <div class="is-size-5 publication-authors"> 
	       <span class="author-block"><sup style="color:#6fbf73;">1</sup>Zhejiang University </span>
	       <span class="author-block"><sup style="color:#ffac33;">2</sup>Dalian University of Technology </span>
	       <span class="author-block"><sup style="color:#ed4b82;">3</sup>Reallm Labs </span>
	       <span class="author-block"><sup style="color:#007bff;">4</sup>ByteDance Inc </span>
	       <span class="author-block"><sup style="color:#ff0000;">5</sup>The Hong Kong Polytechnic University </span><br>
	      
	      <a href="#" style="text-decoration: none; color: blue;">sy_zhang@zju.edu.cn,</a>
       	      <a href="#" style="text-decoration: none; color: blue;">xiaotian.han@bytedance.com,</a>
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
                  <a href="https://github.com/b7277/InfiGUIAgent.github.io/paper.pdf"
                    class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
          	      <i class="fas fa-file-pdf" style="color:white"></i>
                    </span>
                    <span>Paper</span>
                  </a>
                </span>
		
                <!-- Repo Link. -->
                <span class="link-block">
                  <a href="https://github.com/Reallm-Labs/InfiGUIAgent"
                     class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="fab fa-github"></i>
                    </span>
                    <span>Repository</span>
                  </a>
                </span>
		
		<!-- Zhihu Link. -->
		<!-- <span class="link-block">
		  <a href="https://zhuanlan.zhihu.com/p/14143950360"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/zhihu_logo_website_v2.png" alt="Zhihu Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>Zhihu</span>
		  </a>
		</span> -->

		<!-- openreview Link. -->
		<!-- <span class="link-block">
		  <a href="https://openreview.net/forum?id=I7ODESoF6k"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/openreview_v3.jpg" alt="Zhihu Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>OpenReview</span>
		  </a>
		</span> -->

              <!-- Twitter Link. -->
		<!-- <span class="link-block">
		  <a href="https://x.com/OSAgentSurvey/status/1876301310179660231"
		     class="external-link button is-normal is-rounded is-dark" target='_blank'>
		    <span class="icon">
		      <img src="static/images/twitter_v4.jpg" alt="X Icon" style="width: 20px; height: 20px;"/>
		    </span>
		    <span>Twitter</span>
		  </a>
		</span> -->
  
              </div>
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
          <h2 class="title is-3" id='overview'>Overview</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <p>

 	xxx<br>
  		
    	     <!-- <img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/survey_overview_2.jpg"> -->
  
            </p>
          </div>
        </div>
      </div>
      <!--/ Abstract. -->
    </div>
  </section>


 <section class="section" style="margin-top: -40px !important;">
    <div class="container is-max-desktop">
      <!-- Training. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='training'>Training</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <p>
	    InfiGUIAgent is trained in two stages. <b>Stage 1</b> cultivates fundamental abilities using diverse datasets covering GUI understanding (element recognition and layout comprehension), question answering, instruction grounding, general knowledge, and tool usage. <b>Stage 2</b> introduces native advanced reasoning, employed during both training and inference. This stage follows a cyclical process at each step, consisting of Reflection, Hierarchical Reasoning (strategic and tactical layers), Action, and Expectation. Each step receives the overall task, the history of previous screenshots and reasoning, and the current environment as input. Reflection assesses the previous action’s outcome against its expectation, while Expectation predicts the outcome of the current action for subsequent reflection.
  	    </p>
    		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/method.png">

	    <h3>Stage 1: Training for Fundamental Abilities</h3>
     	    <p>
	  We gathered data covering several GUI tasks from multiple sources to ensure a comprehensive capabilities improvement.The datasets can be categorized into five parts:
	  </p>
   	    <ul>
	     <li>GUI Understanding</li>
	     <li>Grounding</li>
	     <li>Question Answering</li>
	     <li>General Knowledge</li>
	     <li>Tool Usage</li>
	    </ul>
		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/dataset.png">
  
	    <h3>Stage 2: Training for Native Reasoning</h3>
     	    <p>
	  GUI Agents are trained to master advanced reasoning skills: (1) Hierarchical reasoning, which involves task decomposition into strategic and tactical layers for efficient execution, and (2) Expectation-reflection reasoning, enabling self-correction and consistent decision-making through iterative reflection and learning from past actions. These skills are integrated into training datasets for native reasoning. The interaction follows a standard protocol using function calls and responses:
	  </p>
		<img style="max-width: 60%; height: auto; margin-bottom: 20px;" src="static/images/functioncall_format.png">
          </div>
        </div>
      </div>
      <!--/ Training. -->
    </div>
  </section>


<section class="section" style="margin-top: -40px !important;">
    <div class="container is-max-desktop">
      <!-- Result. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='result'>Result</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <p>
	    Below provides the results of different models across three platforms (Mobile, Desk- top and Web) and two element types (Text and Icon) on ScreenSpot:<br>
    		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/result1.png"><br>
  	    Below compares the success rates of InfiGUIAgent with open-source models on AndroidWorld:<br>
    		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/result2.png"><br>
            </p>
          </div>
        </div>
      </div>
      <!--/ Stage1. -->
    </div>
  </section>


  <section class="section" style="margin-top: -40px !important;">
    <div class="container is-max-desktop">
      <!-- Cases. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='cases'>Cases</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <h3>Stage 1:</h3>
	    <p>
	    We demonstrate the fundamental abilities trained in Stage 1 through three cases: 
            </p>
	    <ul>
	     <li>GUI Understanding<br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/case_understanding1.png"></li>
	     <li>Grounding<br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/case_grounding1.png"></li>
	     <li>Question Answering<br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/case_QA1.png"></li>
	    </ul>
	    <h3>Stage 2:</h3>
	    <p>
	    Below we provide two representative cases to demonstrate the reasoning and interaction process of InfiGUIAgent: 
            </p>
	    <ul>
	     <li>Reply to a Message<br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/infiGUIAgentcases_3.png"></li>
	     <li>Creating a New Contact<br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/infiGUIAgentcases_1.png"><br><img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/infiGUIAgentcases_2.png"></li>
	    </ul>
          </div>
        </div>
      </div>
      <!--/ Cases. -->
    </div>
  </section>


  <section class="section">
    <div class="container is-max-desktop">
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='contact'>Contact</h2>
          <div class="content has-text-justified">
            <p>
              Please let us know if you find out a mistake or are interested in contributing by e-mail: <a href='mailto:liuyuhang@zju.edu.cn' target='_blank' class='url'>liuyuhang@zju.edu.cn</a>.
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
          <pre><code>@article{liu2025infiguiagent,
  title={InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection},
  author={Liu, Yuhang and Li, Pengxiang and Wei, Zishu and Xie, Congkai and Hu, Xueyu and Xu, Xinchen and Zhang, Shengyu and Han, Xiaotian and Yang, Hongxia and Wu, Fei},
  journal={arXiv preprint arXiv:2501.04575},
  year={2025}
}</code></pre>
        </div>
      </div>
    </div>
  </div>
</section>

<footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <a class="icon-link" href="https://infiguiagent.github.io/paper.pdf">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/Reallm-Labs/InfiGUIAgent">
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
