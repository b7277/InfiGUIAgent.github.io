---
layout: mydefault
---

<html>

<head>
  <meta charset="utf-8">
  <meta name="description" content="OS Agents: A Survey on MLLM-based Agents for General Computing Devices Control">
  <meta name="keywords" content="InfiCoder-Eval, code-generation, large-language-model, benchmark">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> OS Agents: A Survey on MLLM-based Agents for General Computing Devices Control</title>
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

  <link rel="icon" href="./static/images/survey_title_log.jpeg">

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
        <a class="navbar-item" href="https://github.com/infi-coder">
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
      <img style="max-width: 200px; margin-bottom: -50px;" src="static/images/title_log_v3.jpg">
    </div>
  </div>

  <section class="hero">
    <div class="hero-body">
      <div class="container is-max-desktop">
        <div class="columns is-centered">
          <div class="column has-text-centered">
            <h1 class="title is-1 publication-title" style=" font-size:2.3rem;">OS Agents: A Survey on MLLM-based Agents<br>
            for General Computing Devices Control
            </h1>
            <div class="is-size-5 publication-authors">
              <span class="author-block">
		<a href="#" style="text-decoration: none; color: blue;">Xueyu Hu</a><sup style="color: #6fbf73;">1</sup><sup>,</sup><sup style="color: #ff0000;">†</sup>,
                <a href="#" style="text-decoration: none; color: blue;">Tao Xiong</a><sup style="color: #6fbf73;">1</sup><sup>,</sup><sup style="color: #ff0000;">‡</sup>, 
		<a href="#" style="text-decoration: none; color: blue;">Biao Yi</a><sup style="color: #6fbf73;">1</sup><sup>,</sup><sup style="color: #ff0000;">‡</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Zishu Wei</a><sup style="color: #6fbf73;">1</sup><sup>,</sup><sup style="color: #ff0000;">‡</sup><br>
		<a href="#" style="text-decoration: none; color: blue;">Ruixuan Xiao</a><sup style="color: #6fbf73;">1</sup>,
   		<a href="#" style="text-decoration: none; color: blue;">Yurun Chen</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Jiasheng Ye</a><sup style="color: #ffac33;">2</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Meiling Tao</a><sup style="color: #ed4b82;">3</sup>,  
		<a href="#" style="text-decoration: none; color: blue;">Xiangxin Zhou</a><sup style="color: #007bff;">4</sup><sup>,</sup><sup style="color: #ff0000;">5</sup>,<br>
		<a href="#" style="text-decoration: none; color: blue;">Ziyu Zhao</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Yuhuai Li</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Shengze Xu</a><sup style="color: #a74cfe;">6</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Shawn Wang</a><sup style="color: #aa744c;">7</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Xinchen Xu</a><sup style="color: #6fbf73;">1</sup>      
    		<a href="#" style="text-decoration: none; color: blue;">Shuofei Qiao</a><sup style="color: #6fbf73;">1</sup><br>      
		<a href="#" style="text-decoration: none; color: blue;">Kun Kuang</a><sup style="color: #6fbf73;">1</sup>,  
     		<a href="#" style="text-decoration: none; color: blue;">Tieyong Zeng</a><sup style="color: #a74cfe;">6</sup>, 
  		<a href="#" style="text-decoration: none; color: blue;">Liang Wang</a><sup style="color: #007bff;">4</sup><sup>,</sup><sup style="color: #ff0000;">5</sup>,<br>
      		<a href="#" style="text-decoration: none; color: blue;">Jiwei L</a><sup style="color: #6fbf73;">1</sup>,  
     		<a href="#" style="text-decoration: none; color: blue;">Yuchen Eleanor Jiang</a><sup style="color: #ed4b82;">3</sup>,<br> 
      		<a href="#" style="text-decoration: none; color: blue;">Wangchunshu Zhou</a><sup style="color: #ed4b82;">3</sup>,
        	<a href="#" style="text-decoration: none; color: blue;">Guoyin Wang</a><sup style="color: #f1728c;">8</sup> 
		<a href="#" style="text-decoration: none; color: blue;">Keting Yin</a><sup style="color: #6fbf73;">1</sup>,
		<a href="#" style="text-decoration: none; color: blue;">Zhou Zhao</a><sup style="color: #6fbf73;">1</sup>,<br>
		<a href="#" style="text-decoration: none; color: blue;">Hongxia Yan</a><sup style="color: #ac9bae;">9</sup>,
 		<a href="#" style="text-decoration: none; color: blue;">Fan Wu</a><sup style="color: #516594;">10</sup>,
 		<a href="#" style="text-decoration: none; color: blue;">Shengyu Zhang</a><sup style="color: #6fbf73;">1</sup><sup>,</sup><sup style="color: #ff0000;">*</sup>,
	     	<a href="#" style="text-decoration: none; color: blue;">Fei Wu</a><sup style="color: #6fbf73;">1</sup>,<br>
		</span>
          </div>
	       <div class="is-size-5 publication-authors"> 
	       <span class="author-block"><sup style="color:#6fbf73;">1</sup>Zhejiang University </span>
	       <span class="author-block"><sup style="color:#ffac33;">2</sup>Fudan University </span>
	       <span class="author-block"><sup style="color:#ed4b82;">3</sup>OPPO AI Center </span><br>
	       <span class="author-block"><sup style="color:#007bff;">4</sup>University of Chinese Academy of Sciences </span><br>
	       <span class="author-block"><sup style="color:#ff0000;">5</sup>Institute of Automation, Chinese Academy of Sciences </span><br>
	       <span class="author-block"><sup style="color:#a74cfe;">6</sup>The Chinese University of Hong Kong </span>       
	       <span class="author-block"><sup style="color:##aa744c;">7</sup>Tsinghua University </span>
	       <span class="author-block"><sup style="color:#f1728c;">8</sup>01.ai </span><br>
	       <span class="author-block"><sup style="color:#ac9bae;">9</sup>The Hong Kong Polytechnic University </span>
	       <span class="author-block"><sup style="color:#516594;">10</sup>Shanghai Jiao Tong University </span><br>

	      <a href="#" style="text-decoration: none; color: blue;">{huxueyu, sy_zhang}@zju.edu.cn</a>	 

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
                  <a href="https://arxiv.org/abs/2404.07940"
                    class="external-link button is-normal is-rounded is-dark" target='_blank'>
                    <span class="icon">
                      <i class="ai ai-arxiv"></i>
                    </span>
                    <span>Paper</span>
                  </a>
                </span>
                <!-- Dataset Link. -->
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
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="hero teaser">
    <div class="container is-max-desktop">
      <div class="hero-body">
        <h2 class="subtitle">
          The dream to create AI assistants as capable and versatile as the fictional J.A.R.V.I.S from Iron Man has long captivated imaginations. With the evolution of (multimodal) large language models ((M)LLMs), this dream is closer to reality, as (M)LLM-based Agents operating within the environments and interfaces (e.g., Graphical User Interface (GUI)) provided by operating systems (OS) to automate tasks have significantly advanced. This paper presents a comprehensive survey of these advanced agents, designated as OS Agents. We begin by elucidating the fundamentals of OS Agents, exploring their key components including the environment, observation space, and action space, and outlining essential capabilities such as understanding, planning and grounding. We then examine methodologies for constructing OS Agents, focusing on domain-specific foundation models and agent frameworks. A detailed review of evaluation protocols and benchmarks highlights how OS Agents are assessed across diverse tasks. Finally, we discuss current challenges and identify promising directions for future research. This survey aims to consolidate the state of OS Agents research, providing insights to guide both academic inquiry and industrial development.
        </h2>
<!--         <img src="static/images/inficoder-eval-main.png"> -->
      </div>
    </div>
  </section>

  <section class="section">
    <div class="container is-max-desktop">
      <!-- Abstract. -->
      <div class="columns is-centered has-text-centered">
        <div class="column is-four-fifths">
          <h2 class="title is-3" id='overview-of-xxx'>Overview of Survey</h2>
          <div class="content has-text-justified" style="font-size: 1.1rem;">
            <p>
 		<img style="max-width: 100%; height: auto; margin-bottom: 20px;" src="static/images/survey_overview_2.jpg">
		    
	This survey aims to make contributions to the research and development of OS Agents by providing readers with a comprehensive understanding of their essential capabilities, offering insights into methodologies for building OS Agents based on (M)LLMs, and highlighting the latest research trends, challenges and future in this field. Recognizing that OS Agents are still in their early stages of development, we acknowledge the rapid advancements that continue to introduce novel methodologies and applications. Through this work, we aspire to inspire further innovation, driving progress in both academic research and industrial applications of OS Agents.
  
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

  

  <footer class="footer">
    <div class="container">
      <div class="content has-text-centered">
        <a class="icon-link" href="https://arxiv.org/abs/2404.07940">
          <i class="fas fa-file-pdf" style="color:white"></i>
        </a>
        <a class="icon-link" href="https://github.com/infi-coder" class="external-link" disabled>
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
              This means you are free to borrow the <a href="https://github.com/infi-coder/infibench">source
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
