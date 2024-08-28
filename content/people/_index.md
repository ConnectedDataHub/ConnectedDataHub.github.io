---
title: "People"
layout: "list"
date: 2024-05-23T15:32:56-04:00
draft: false
featured_Image: "/images/DSBUILDING2.jpg"
menu: "main"
weight: 2
params:
  text_color: 'black'
  background_color_class: "bg-white"
  body_classes: 'helvetica bg-white'
  post_content_classes: 'helvetica bg-white'
  custom_css: "custom.css"

---

<style>
  .projects-container {
    display: flex;
    flex-direction: column;
    gap: 20px; /* Adjust the space between projects as needed */
  }

  .project {
    display: flex;
    align-items: center;
    border-bottom: 1px solid #ccc; /* Add border line between projects */
    padding-bottom: 10px;
    margin-bottom: 10px;
  }

  .project img {
    width: 200px; /* Adjust image size as needed */
    height: auto;
    margin-right: 20px; /* Space between image and text */
  }

  .project-description {
    flex: 1; /* Make description take remaining space */
    text-align: left;
    padding-left: 10px;
  }

  .profile-image {
      width: 150px; /* Adjust size as needed */
      height: 150px; /* Ensure height and width are the same */
      object-fit: cover; /* Ensure the image covers the circle without distortion */
      border-radius: 50%; /* Make the image circular */
  }
</style>

<div class="projects-container">
  <div class="project">
    <div class="project-description">
      <h3>Alexander Gates</h3>
      <div style="float: right; margin-left: 1em; margin-bottom: 1em;">
        <img src="/images/ajg_image.jpeg" alt="Description of the image" class="profile-image">
      </div>
      <p>
      Alex Gates is an Assistant Professor in the School of Data Science at the University of Virginia where he directs the Connected Data Hub. Prior to joining UVA in 2022, he was an Associate Research Scientist in Northeastern University’s Network Science Institute and the Department of Sociology. Alex is a Network Science with theory from Sociology—to draw insights from large datasets and uncover the interplay between the behaviors of individuals and the emergent structure of organizations, societies, and markets. Specifically, his research focuses on the Science of Science to analyze and model how organizational structure and strategic decisions impact innovation, creativity, and success. His work has been featured in top journals including Nature, The Proceedings of the National Academy of Sciences, andThe Journal of Machine Learning. Alex holds a joint Ph.D. in Informatics (complex networks) and Cognitive Science from Indiana University, Bloomington, a M.Sc. from King's College London in complex systems modeling and a B.A. in mathematics from Cornell University. <br>
      <a href="https://alexandergates.net" target="_blank">alexandergates.net</a>
      </p>
    </div>
  </div>

  <div class="project">
    <div class="project-description">
      <h3>Project 2</h3>
      <div style="float: right; margin-left: 1em; margin-bottom: 1em;">
        <img src="/images/beyonce_picture.png" alt="Description of the image" class="profile-image">
      </div>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
      <a href="https://example.com/project1" target="_blank">Learn more</a></p>
    </div>
  </div>

  <div class="project">
    <img src="/images/beyonce_picture.png" alt="Project 3 Image">
    <div class="project-description">
      <h3>Project 3</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <a href="https://example.com/project1" target="_blank">Learn more</a></p>
    </div>
  </div>
  <div class="project">
    <img src="/images/beyonce_picture.png" alt="Project 4 Image">
    <div class="project-description">
      <h3>Project 4</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <a href="https://example.com/project1" target="_blank">Learn more</a></p>
    </div>
  </div>
</div>
