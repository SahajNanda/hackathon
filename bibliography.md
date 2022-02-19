---
layout: default
title: "Bibliography Creator"
---
&nbsp; Insert the necessary information below to recieve your citation.
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
      <label for="websiteAuthor">Author:</label>
      <input type="text" id="websiteAuthor" name="websiteAuthor"><br>
      <label for="websiteTitle">Article Title:</label>
      <input type="text" id="websiteTitle" name="websiteTitle"><br>
      <label for="websiteName">Website Title</label>
      <input type="text" id="websiteName" name="websiteName"><br>
      <label for="websiteURL">Full URL:</label>
      <input type="text" id="websiteURL" name="websiteURL"><br>
      <label for="websitePublisher">Publisher:</label>
      <input type="text" id="websitePublisher" name="websitePublisher"><br>
    </form>
  </div>
  
  
  
  <script>
  $('#type').on('change',function(){
    if($(this).val()==="website"){
      $("#websiteInfo").hide()
  }}
  </script>
