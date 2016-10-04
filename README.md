#Placester exercise

## Installation

Install slim

``` gem install slim ```

With gulp installed, you should be able to run

``` npm install ```

and

``` gulp ```

and everything should spin up alright.

## Review
For this exercise I time-boxed about 6 hours to work. I took the directions to heart that this would be one page of a many page website. 

All the work is in the ```lib``` directory and compiles to ```dist``` for "production" (in this case, viewing on a simple server on localhost.

The assets are compressed for production, and the styles are compressed and concatenated for a single load point.

The layout is a simple flexbox layout with the opportunity to add shims for IE8+, though in this instance I did not add them. I also did not implement breakpoints with this exercise, though flexbox offers a relatively simple mechanism for orienting content in a single column on mobile displays (with flex-direction row vs column). I like to think through responsive displays as a function of content rather than device screen size, this offers better layouts for content on every screensize, rather than forcing awkward breaks at standard 320/480/... sizes and "future-proofs" content for the introduction of new and different devices to the market.

I tried to organize this work intuitively, though there is more refactoring opportunity here to bring things up to a production ready state that I was not able to do in my time-boxed effort. The photo-slider here is an easy candidate for extracting out into a scss component. This would allow the styles to live in the components sub-folder and be implemented with relative ease in other locations on the site. In a react/angular/... environment, the markup would also be written in the component for further organization and ease of re-use.

I'm happy to talk through any of the work I was able to do, including strategies for handling site-wide breakpoints, typography, colors and look/feel styles, etc. I appreciate the opportunity to work on an exercise for you and show some of the thought behind how I write code. Hopefully this is a step in the right direction, though building a full responsive website designed for extensibility, reuse, and many developers is a large undertaking, and in my honest opinion, a lot to ask for a code exercise pre-interview. That being said, I hope my personal style of coding is well-exemplified here and I'd appreciate any feedback or changes with regard to the coding standards of Placester or your front-end developers' opinions and best practices. As with anything in programming, there's always more to learn.

Thanks,
-Paul
