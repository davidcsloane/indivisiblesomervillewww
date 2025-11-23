Indivisible Somerville Website 
=====

### Running the website on your personal computer

The following instructions are for running the website locally on 
your development environment.

1. [**Setup Jekyll**](https://jekyllrb.com/docs/installation/)

2. **Clone this repo**:
   In a terminal, change to the directory where you would like to host this
   repo, and run `git clone`:
   
   ```git clone git@github.com:davidcsloane/indivisiblesomervillewww.git```

   navigate to the root directory: `cd indivisiblesomervillewww`

3. **Run `jekyll`**: `jekyll build && jekyll serve`
   
4. **Load the page in the browser**: type (or copy) the url `https://localhost:4000`
   into your browser. You should be able to see the page.

### Analyzing the webpage for accessibility and usability issues

We use [Lighthouse](https://developer.chrome.com/docs/lighthouse) to analyze
a number of factors that directly impact usability and, consequently, how 
highly the webpage is ranked on Google and Bing. Before we check changes, 
we need to make sure that we are not negatively impacting these factors
to avoid hurting viewer experience and the rank of the website.

To do this, please:

1. use the guide for [running the website locally](#running-the-website-on-your-personal-computer) to spin up a local version of the website at `http://localhost:4000`. 

2. open Lighthouse in Developer's Tool. (Skip if you plan to use
   Lighthouse as a standalone command-line application.)

4. follow the instructions for [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview#devtools) or
   [command line application (CLI)](https://developer.chrome.com/docs/lighthouse/overview#cli)

5. pay attention to Page Speed
