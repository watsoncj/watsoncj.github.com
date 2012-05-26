---
layout: default
title: Casey Watson
tagline: about
---
{% include JB/setup %}

<div class="page-header">
  <h1>Hi, I'm Casey <small>Dad, Husband and Programmer</small></h1>
</div>
##I build <em>epic</em> software with the <em>rad</em> people at <a href="http://readytalk.com">ReadyTalk</a>

<hr/>


<div class="row">
  <div class="span5">
    <h2>Don't cross the streams</h2>
    <div id="lifestream">
    </div>
  </div>
<!--  <form class="span3">
    <div class="control-group">
      <label><h2>Contact</h2></label><textarea class="input-large">Howdy!</textarea>
    </div>
    <button type="submit" class="btn btn-primary">Save changes</button>
  </form>
-->
</div>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js">
</script>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.1/jquery.min.js">
</script>

<script src="/assets/js/jquery.lifestream.js">
</script>

<script>

  $("#lifestream").lifestream({
    limit: 300,
    list:[
      {
        service: "github",
        user: "watsoncj"
      },
      {
        service: "twitter",
        user: "watsoncj"
      },
      {
        service: "bitbucket",
        user: "watsoncj"
      },
      {
        service: "stackoverflow",
        user: "watsoncj"
      },
      {
        service: "vimeo",
        user: "watsoncj"
      }
    ]
  });

</script>

