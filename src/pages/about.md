---
layout: ../layouts/AboutLayout.astro
title: "About"
---

I'm a writer based out of Boston with 9 years experience in copy, 6 in content design and technical docs. I'm open to full-time and contract roles.

My passions are TTRPGs, writing romance, drawing, and all things medieval. I spend most of my time playing video games and yelling (with love) at my toddler (cat).

<table class="about-experience">
  <tbody>
    <tr>
      <td>VRChat</td>
      <td>Technical Writer/Content Designer</td>
      <td>2023-Now</td>
    </tr>
    <tr>
      <td>Discord</td>
      <td>Content Designer/Copywriter</td>
      <td>2018-2022</td>
    </tr>
    <tr>
      <td>Zotac</td>
      <td>Marketing Writer</td>
      <td>2018-2018</td>
    </tr>
    <tr>
      <td>Various Startups</td>
      <td>Freelance Esports Journalist</td>
      <td>2015-2018</td>
    </tr>
  </tbody>
</table>
<style>
    .about {
        display: flex;
        flex-wrap: wrap;
        align-items: flex-start;
        justify-content: space-around;
    }

    .about-image {
        flex: 1 0 35%;
        text-align: center;
    }

    .about-image img { 
        display: inline-block; 
        width: 300px;
        margin-bottom: 20px;
    }

    .about-text {
        flex: 1 0 50%;
        padding-left: 2em;
        float:right;
    }

    .about-text > h2 { margin: 0; }

    .about-text > p {
        font-size: 18px;
        line-height: 24px;
    }

    .about-experience table {
        table-layout: fixed;
        width: 100%;
        margin: 1em 0;
    }

    .about-experience td {
       border-bottom-width: 1px;
       @apply border-skin-line;
    }

    .about-experience td:nth-child(1) {
        width: 30%;
        font-weight: bold;
    }

    .about-experience td:nth-child(2) {
        width: 40%;
        text-align: center;
    }

    .about-experience td:nth-child(3) {
        width: 30%;
        text-align: right;
    }

    .about-experience tr:nth-child(1) {
      border-top-width: 1px;
      @apply border-skin-line;
    }

    table.about-experience tr, td {
        padding: 10px 0;
    }
</style>

<div>
  <img src="/assets/jesurkaresize.png" class="sm:w-1/2 mx-auto" alt="coding dev illustration">
</div>
