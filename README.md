<div id="top"></div>
<div align="center">
 
  <h1 align="center">17. Computer Science for JavaScript Challenge: Regex Tutorial</h1>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/LKocaj/17-regex-tutorial"><strong>github</strong></a>
  </p>
</div>
 



<!-- TABLE OF CONTENTS -->
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#user-story">User Story</a></li>
        <li><a href="#acceptance-criteria">Acceptance Criteria<a></li>
      </ul>
    </li>
    <li><a href="#what-is-a-regex">What is a Regex?</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>

<!-- ABOUT THE PROJECT -->
## About The Project

Developers write code, but they also write about code.

The challenge this week is to create a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does.



<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started
<br>

<!-- User Story -->
### User Story
```sh
AS A web development student

I WANT a tutorial explaining a specific regex

SO THAT I can understand the search pattern the regex defines
  ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Acceptance Criteria -->
### Acceptance Criteria

```sh
GIVEN a regex tutorial

WHEN I open the tutorial

THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile

WHEN I click on the links in the table of contents

THEN I am taken to the corresponding sections of the tutorial

WHEN I read through each section of the tutorial

THEN I find a detailed explanation of what a specific component of the regex does

WHEN I reach the end of the tutorial

THEN I find a section about the author and a link to the author’s GitHub profile
  ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- What is a regex? -->
## What is a Regex?

A regex, which is short for regular expression, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input.

For example, the following regular expression can be used to verify that user input is a valid email address:
```
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the @ symbol, followed by a domain.

Before you get started, watch this introduction to regular expressions video (Links to an external site.) and read this Regex Tutorial (Links to an external site.) to learn how to identify the different components that make up a regex. If you need any additional help, there are many resources on the web. Feel free to do your own research to find one that can help you complete this Challenge.

Once you have a better understanding of what these different parts of a regular expression do, you’ll need to explain what they do for a specific regex.

You can choose one of the following regular expressions or you can choose one that you found on your own (with the exception of the one that was covered in the virtual classes, Matching a Username):

Matching a Hex Value
```
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/ 
```

Matching an Email 
``` 
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```
Matching a URL
```
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
```
Matching an HTML Tag –
```
/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/
```
<!-- CONTACT -->
## Contact

Email: Lawrencecaj@gmail.com
<br>
<br>
Youtube: https://www.youtube.com/channel/UCT9VNw7nEAY0jqPlHM6zlSw
<br>
<br>
Project Link: https://github.com/LKocaj/17-regex-tutorial

<p align="right">(<a href="#top">back to top</a>)</p>