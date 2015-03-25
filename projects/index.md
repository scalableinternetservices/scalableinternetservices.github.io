---
layout: page
title: Course Project
description: Description of Course Project
categories: ['presentations']
showinnav: false
---
<div class="content">
  <h2>Objective</h2>

  <p>
  The goal of the project is to gain hands-on experience in building and
  deploying a scalable web service on the Internet.  Using the latest web
  technologies while learning how to tackle the scalability and
  fault-tolerance concerns. This is a "learn by doing" course: the course
  project will form the primary focus of the course with the lectures and
  discussion of research papers providing background material. Each project
  will be conducted in an agile team where students will build their own
  scalable, redundant web site using fundamental web technologies and the
  Ruby on Rails framework.  
  </p>


  <h2>Getting Started</h2>

  <ul>
    <li>Follow Chapter 1 of the book (Agile Web Development with Rails 4)
    for installation instructions of Rails for Windows, Mac, or Linux</li>
    <li>Read the list of <a href="#project_ideas">project suggestions</a></li>
    <li>Add your own project suggestions</li>
  </ul>
  
  <h2>Fall 2014 Projects</h2>
  <ul>
    <li><a href="https://github.com/scalableinternetservices/Gradr">A scalable automatic grading system</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Compete">A competition tracking application</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/LaPlaya">Share programming projects like MIT's Scratch</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/BaconWindshield">Find and compare nearby surf spots</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Upvid">Upload and share viral videos</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Picshare">Send photos to strangers, and upvote/downvote them</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Motley-Crew">Questmaster: gamification of everyday tasks</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Xup">Find parties near you and share yours</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Team-Hytta">An electronic cabin guest book</a>.</li>
    <li><a href="https://github.com/scalableinternetservices/Suppr">Suppr: share meals with friends</a>.</li>
    
  </ul>

  <a id="project_ideas"></a>
  <h2> Project Ideas </h2>
  <ul>
    <li> YCombinator inspired: YC <a href="http://www.ycombinator.com/rfs/">Request for Startups</a> Implement some portion of one of the YCombinator "Startup ideas we would like to fund" </li>
    <li> 
    Government data project. A system that uses the large amounts of
    data at <a href="http://data.gov">data.gov</a> or the <a href="http://aws.amazon.com/publicdatasets/">amazon public data sets</a>, see the <a href="http://sunlightfoundation.com/projects/">sunlight
      foundation</a> projects for some ideas.
    </li>
    <li>
      Leverage the data from the <a href="http://developer.nytimes.com/docs"> New York Times Developer
      APIs </a> in order to build something interesting.  They have APIs
      convering geography, movie reviews and more.
    </li>
    <li>
      Embrace the sharing economy!  Build a time-sharing app for pets.
      Own 30% of a dog.
    </li>
    <li>
    Stock trade advisor. A system that gathers information about stocks,
    stock trades, and companies from both traditional and non-traditional
    sources (blogs, email lists, twitter feeds, facebook) and computes
    interesting data. Potential interesting data would be correlations
    between stock price and both non-traditional data, trending information
    based on non-traditional sources. Could also include social aspects for
    submitting sources, voting for impact of source, etc.

    </li>
  </ul>

  <h2> Project Sprint Schedule </h2>

  <ul>
    <li>
    <b>Sprint -1: Starts April 3, 2015.</b>
    <ul>
      <li>Install Rails</li>
      <li>Learn Ruby</li>
      <li>Do <a href="http://www.codecademy.com/en/tracks/ruby">Ruby Code Academy</a></li>
      <li>Learn Rails</li>
      <li>Read Chapters one through eight in Agile Web Development with Rails</li>
    </ul>
    </li>
    <li>
    <b>Sprint 0: Starts April 10, 2015.</b>
    <ul>
      <li>By the beginning of this sprint, you should have your team
      formed.</li>
      <li>Determine your project, get approved by TA and professor.</li>
      <li>Read chapters nine through seventeen in Agile Web Development with Rails</li>
      <li>If you don't know git, learn git: <a
      href="http://rogerdudler.github.io/git-guide/">simple guide</a>
      </li>
    </ul>
    </li>

    <li>
    <b>Sprint 1: Starts April 17, 2015.</b>
    <ul>
      <li>Get a blank rails app in your team's github repo.</li>
      <li>Learn TDD: get <a href="http://docs.travis-ci.org">Travis CI</a> working with your github repository</li>
      <li>Start writing stories for your project in pivotal tracker</li>
      <li>Decide on a sprint commitment.</li>
      <li>Learn pairing by pairing up on the first few stories</li>
    </ul>
    </li>

    <li>
    <b>Sprint 2: Starts April 24, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Decide on a sprint commitment.</li>
      <li>Implement stories from the current sprint.</li>
      <li>Deploy your application on Amazon EC2 (it's fine if the apps
      functionality is very limited at this point).</li>
      <li>Learn EC2 and Amazon Web Console</li>
    </ul>
    </li>


    <li>
    <b>Sprint 2: Starts May 1, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Decide on a sprint commitment.</li>
      <li>Implement stories from the current sprint.</li>
      <li>Deploy a tsung instance on EC2.</li>
      <li>Write an initial tsung xml file to load test a simple action
      on your app.</li>
      <li>Load test your app with tsung running on a micro instance.</li>
    
    </ul>
    </li>

    <li>
    <b>Sprint 3: Starts May 8, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Decide on a sprint commitment.</li>
      <li>Implement stories from the current sprint.</li>
      <li>Define the "critical path" through your application (the set
      of pages that a common user will go through)</li>
      <li>Write a tsung xml file to exercise this critical path.</li>
      <li>Test (and document) the effects of vertical scaling on your
      application with the new critical path xml file.</li>
      <li>Create medium-large dataset (~10,000 records) using
      database seeds and perform the vertical scaling tests against this
      as well.</li>

    </ul>
    </li>


    <li>
    <b>Sprint 4: Starts May 15, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Decide on a sprint commitment.</li>
      <li>Implement stories from the current sprint.  Your application
      should be mostly feature complete at this time and subsequent work
      should focus on polish.</li>
      <li>Deploy your application on a variety of load-balanced
      configurations, with large dataset.  Tsung test, measure,
      document.</li>
    </ul>
    </li>


    <li>
    <b>Sprint 5: Starts May 22, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Decide on a sprint commitment.</li>
      <li>Implement stories from the current sprint.  Only polish is
      appropriate at this stage.</li>
      <li>By the end of this sprint your project should be feature complete.</li>
      <li>Inspect and optimize the way your application is interacting
      with the database.  If necessary, write custom sql to optimize.</li>
      <li>Deploy your data-related optimizations on a simple load-balanced
      configuration, with large dataset.  Tsung test, measure,
      document.</li>
    </ul>
    </li>


    <li>
    <b>Sprint 6: Starts May 29, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Create large dataset (greater than 100,000 records)</li>
      <li>Implement server-side caching.</li>
      <li>Deploy your caching optimizations on a simple load-balanced
      configuration, with large dataset, both with and without memcache.  Tsung test, measure,
      document.</li>
    </ul>
    </li>


    <li>
    <b>Sprint 7: Starts June 5, 2015.</b>
    <ul>
      <li>Conduct a retrospective on how the last sprint went and how
      you can improve.</li>
      <li>Final performance experiments</li>
      <li>Document measurements</li>
      <li>Test for Availability</li>
      <li>Writeup results</li>
      <li>Prepare final presentation</li>
    </ul>
    </li>


    <li>
    <b>Final Presentation date TBD</b>
    <ul>
      <li>Final Presentations</li>
    </ul>
    </li>


  </ul>
</div>
