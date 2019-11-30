---
layout: default
title: "Political Argument Generator"
description: "Generate political arguments that make as much sense as anything else you see online these days."
---
<div class="container">

  <h1 style="text-align:center;">Political Argument Generator</h1>
  <p>Generate political arguments that make as much sense as anything else you see online these days.</p>
  <form style="width:320px;margin:auto;">
    <div class="form-group">
      <label for="paragraphs"># of Paragraphs</label>
      <select class="form-control" id="paragraphs">
        <option>1</option>
        <option selected>2</option>
        <option>3</option>
        <option>4</option>
        <option>5</option>
      </select>
    </div>
    <div class="form-group">
      <label for="sentenceMin">Min Sentences per Paragraph</label>
      <select class="form-control" id="sentenceMin">
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option selected>5</option>
        <option>6</option>
        <option>7</option>
        <option>8</option>
        <option>9</option>
      </select>
    </div>
    <div class="form-group">
      <label for="sentenceMax">Max Sentences per Paragraph</label>
      <select class="form-control" id="sentenceMax">
        <option>1</option>
        <option>2</option>
        <option>3</option>
        <option>4</option>
        <option>5</option>
        <option>6</option>
        <option>7</option>
        <option>8</option>
        <option selected>9</option>
      </select>
    </div>
    <div style="text-align:center"><button id="gen" type="button" class="btn btn-primary">Generate</button></div>
  </form>

  <div id="generated" style="padding-top:48px;max-width:640px;margin:auto;text-align:left;"></div>

</div>

<script src="main.js"></script>
