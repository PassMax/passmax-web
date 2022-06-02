<style>
  @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=PT+Sans&display=swap');
  #center{
    text-align: center;
    font-family: 'PT Sans', sans-serif;
  }
  #center-p{
    text-align: center;
    font-family: 'PT Sans', sans-serif;
    margin-top: 15px;
  }
  code{
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #outer{
    width:100%;
    text-align: center;
  }
  #inner{
    display: inline-block;
  }
  #btn{
    margin-left: 15px;
  }
  button{
    margin-top: 15px;
    margin-bottom: 50px;
  }

  #icon{
    display: flex;
    justify-content: center;
    align-items: center;
  }  
  
</style>

<script>
  function goToInstall(){
    window.location.href = "https://www.github.com/PassMax/PassMax/wiki/Installation";
  }

  function goToDocumentation(){
    window.location.href = "https://www.github.com/PassMax/PassMax/wiki/";
  }
</script>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css">

<h1 id="center" class="title is-1">PassMax</h1>

<div id="icon">
  <img src="src/icon.png" alt="icon" width="350" height="350">
</div>


<p id="center">A minimal Password manager built with python!</p>

<div id="outer">
  <div id="inner">
    <button type="submit" class="button is-primary is-outlined is-rounded" id="btn" on:click={goToInstall}>Install</button>
  </div>
  <div id="inner">
    <button type="submit" class="button is-primary is-outlined is-rounded" on:click={goToDocumentation}>Documentation</button>
  </div>
</div>


<h2 id="center-p" class="title">What Is PassMax?</h2>
<p id="center">PassMax Is Password manager to manage your passwords</p>
<p id="center">It's desigened to be <strong>User Centric</strong> not <strong>User Friendly</strong></p>

<h2 id="center-p" class="title">Installation</h2>

<p id="center">On MacOS/Linux you can install it by running the following command:</p>

<pre>
  <code>
  curl -sL https://raw.githubusercontent.com/passmax/passmax/master/install.sh | bash
  </code>
</pre>

<p id="center-p">On Windows please refer to the <a href="https://www.github.com/PassMax/PassMax">Documentation</a> </p>