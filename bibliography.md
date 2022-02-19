---
layout: default
title: "Bibliography Creator"
---
&nbsp; Insert the necessary information below to recieve your citation (test2).
<label for="type"><br>&nbsp; Choose a source:</label>
  <select name="type" id="type">
    <option value="website">website</option>
    <option value="book">book</option>
    <option value="youtube">youtube</option>
    <option value="twitter">twitter</option>
  </select>
  <br><br>
  <div id="websiteInfo">
    <form>
      <label for="websiteAuthor">&nbsp;Author: </label>
      <input type="text" id="websiteAuthor" name="websiteAuthor"><br>
      <label for="websiteTitle">&nbsp;Article Title: </label>
      <input type="text" id="websiteTitle" name="websiteTitle"><br>
      <label for="websiteName">&nbsp;Website Title: </label>
      <input type="text" id="websiteName" name="websiteName"><br>
      <label for="websiteURL">&nbsp;Full URL: </label>
      <input type="text" id="websiteURL" name="websiteURL"><br>
      <label for="websitePublisher">&nbsp;Publisher: </label>
      <input type="text" id="websitePublisher" name="websitePublisher"><br>
    </form>
  </div>
  
  
<script type="text/javascript" src="jquery-ui-1.10.0/tests/jquery-1.9.0.js"></script>
<script src="jquery-ui-1.10.0/ui/jquery-ui.js"></script>
  <script>
  $('#type').on('change',function(){
    if( $(this).val()==="website"){
      $("#websiteInfo").hide()
  }}
  </script>
